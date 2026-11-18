<script setup>
</script>

<template>
    <div class="p-10">
        <div class="d-flex flex-column gap-10">
            <!-- FORMULÁRIO -->
            <h1 class="text-center fw-bold">Cadastro de Tarefas</h1>
            <div class="w-100 d-flex justify-content-center align-items-center">
                <div class="w-25 d-flex flex-column gap-6">
                    <div class="form-field">
                        <label class="form-label">Título da tarefa</label>
                        <input type="text" class="form-control" />
                    </div>
                    <div class="form-field">
                        <label class="form-label">Descrição da tarefa</label>
                        <input type="text" class="form-control" />
                    </div>
                    <button class="btn-solid theme-success">Salvar</button>
                </div>
            </div>
            <!------------------------------------------------------------------------>

            <!-- LISTAGEM DE TAREFAS -->
            <div>
                <h2 class="text-sm m-0">Trefas cadastrados: 0</h2>
            </div>
            <div class="grid grid-cols-4">
                <section class="card h-fit" style="max-width: 320px">
                    <div class="card-body">
                        <h4 class="card-title fw-bold">Tarefa 1</h4>
                        <p class="card-text">Descrição</p>
                        <span>26/11/2026</span>
                        <div class="d-flex gap-6">
                            <div class="w-100">
                                <button class="btn-solid theme-info w-100">
                                    Editar
                                </button>
                            </div>
                            <div class="w-100">
                                <button class="btn-solid theme-danger w-100">
                                    Excluir
                                </button>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
        </div>
    </div>
</template>
