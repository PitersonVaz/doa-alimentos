# DoaAlimentos - Plataforma de Combate ao Desperdicio e Seguranca Alimentar

MVP de Solucao de Impacto Social: Plataforma voltada a redistribuicao do excedente de alimentos entre doadores (supermercados, hortifrutis, padarias) e receptores (ONGs, cozinhas comunitarias), em conformidade com as diretrizes da ANVISA e a Lei nº 14.016/2020.

Link para testar o prototipo rodando ao vivo: https://doacao-alimentos.netlify.app

---

## O Problema
Milhares de toneladas de alimentos proprios para consumo sao descartados diariamente por estabelecimentos comerciais devido a proximidade do vencimento ou questoes esteticas, enquanto instituicoes sociais enfrentam escassez de recursos para manter suas cozinhas comunitarias.

## A Solucao
O DoaAlimentos e uma aplicacao web projetada para intermediar a doacao segura de alimentos, garantindo governanca sanitaria e rastreabilidade do processo.

### Funcionalidades Principais:
- Gestao Cadastral e Homologacao: Modulo restrito ao Administrador para validacao de CNPJ e Alvara Sanitario antes da liberacao do perfil.
- Painel do Doador: Formulario de publicacao de lotes com Checklist Obrigatorio de Conformidade ANVISA (integridade de embalagem, temperatura e validade).
- Painel do Receptor: Feed dinamico de lotes ordenados por urgencia de vencimento, utilizando alertas visuais por cores (Validade OK, Vencimento Proximo e Urgente).
- Termo Digital de Coleta: Aceite digital do resgate simulando a transferencia de responsabilidade sanitaria conforme a Lei 14.016/2020.

---

## Tecnologias Utilizadas
- Frontend: HTML5, Tailwind CSS
- Logica e Estado: JavaScript (Vanilla JS com persistencia em localStorage)

---

## Como Executar o Projeto Localmente
1. Clone este repositorio:
   git clone https://github.com/PitersonVaz/doa-alimentos.git
2. Abra o arquivo doa-alimentos-mvp.html em qualquer navegador web moderno.
