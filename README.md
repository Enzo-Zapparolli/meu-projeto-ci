# meu-projeto-ci

## Validação da Parte 3

Saída do comando `act -l`:

```text
Stage  Job ID             Job name             Workflow name          Workflow file                    Events
0      teste-basico       teste-basico         01 Hello Local         01-hello-local.yml              workflow_dispatch,push
0      setup-e-lint       setup-e-lint         02 Pipeline Principal  02-pipeline-principal.yml       push
1      testes-unitarios   testes-unitarios     02 Pipeline Principal  02-pipeline-principal.yml       push
1      scan-de-seguranca  scan-de-seguranca    02 Pipeline Principal  02-pipeline-principal.yml       push
2      build-e-deploy     build-e-deploy       02 Pipeline Principal  02-pipeline-principal.yml       push
