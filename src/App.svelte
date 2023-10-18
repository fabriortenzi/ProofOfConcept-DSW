<script>
  let todos = [
		{ done: false, text: 'Aprender Svelte' },
		{ done: false, text: 'Ir al supermercado' },
		{ done: false, text: 'Estudiar SQL' }
	];

	function add() {
		todos = todos.concat({ done: false, text: '' });
	}

	function clear() {
		todos = todos.filter((t) => !t.done);
	}

	$: remaining = todos.filter((t) => !t.done).length;
</script>

<main>
  <h1>Tareas</h1>

  {#each todos as todo}
    <div class="task-item">
      <input type="checkbox" bind:checked={todo.done} />

      <input class="task-text" type="text" placeholder="Qué tarea quieres agregar?" bind:value={todo.text} disabled={todo.done} />
    </div>
  {/each}

  {#if todos.length == 0}
    <p class="remaining-text">No tienes más tareas, felicitaciones!</p>
  {:else}
    <p class="remaining-text">{remaining} restantes</p>
  {/if}

  <button on:click={add}> Añadir </button>

  <button on:click={clear}> Borrar completadas </button>
</main>

<style>
  .task-item {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    margin: 10px 0;
  }

  .task-text {
    font-family: inherit;
    border-radius: 10px;
    border: 1.5px solid #1a1a1a;
    transition: .2s;    
    height: 30px;
    width: 300px;
    padding-left: 20px;
  }

  .task-text:focus {
    outline: none;
    background-color: #3f3f3f;
    transition: .2s;
  }

  .remaining-text {
    margin-top: 30px;
  }
</style>
