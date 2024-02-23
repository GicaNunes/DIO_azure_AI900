# DIO_azure_AI900

utilizando o modelo do laboratório: 
na aba Modelo, selecionei implantar, usei a opção: serviços web.

preenchi quase (rsrsrs) como o modelo proposto pela Azure. 
nome: previsao
descrição: previsao de aluguel de bikes
tipo da computação: instância de containers
habilitar autenticação: selecionado.

esperei( deu ruim rsrsrs apareceu unhealthy, desesperei, respirei e recebi a notificação que estava carregado)depois de tudo verificado. 
escolhe o modelo dentro do modelo ou na aba esquerda pontos de extremidade: clica em previsao (nome escolhido) e escolhe a aba testar. e é so fazer o teste.
ah nao esqueçam de verificar o estado da operação: tem estar succeeded! 




arquivo json
{
data =  {
  "Inputs": {
    "data": [
      {
        "day": 0,
        "mnth": 0,
        "year": 0,
        "season": 0,
        "holiday": 0,
        "weekday": 0,
        "workingday": 0,
        "weathersit": 0,
        "temp": 0.0,
        "atemp": 0.0,
        "hum": 0.0,
        "windspeed": 0.0
      }
    ]
  },
  "GlobalParameters": 0.0
}


