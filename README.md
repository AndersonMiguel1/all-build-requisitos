# all-build-requisitos
// Script JS para análise de requisitos de sistema

const requisitos = [
    { id: 1, descricao: "Cadastro de funcionários", funcional: true, prioridade: "Alta" },
    { id: 2, descricao: "Cálculo de horas extras", funcional: true, prioridade: "Média" },
    { id: 3, descricao: "Relatório de folha de pagamento", funcional: false, prioridade: "Alta" }
];

function analisarRequisitos() {
    console.log("Análise de Requisitos para All-Build:");
    requisitos.forEach(req => {
        console.log(`ID: ${req.id} - ${req.descricao} (${req.funcional ? "Funcional" : "Não Funcional"}) - Prioridade: ${req.prioridade}`);
    });
}

analisarRequisitos();
