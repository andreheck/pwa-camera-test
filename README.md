# PWA Camera Test

Página isolada para testar `getUserMedia` (acesso à câmera) especificamente em
modo **standalone** de PWA no iOS — fora do contexto do app principal PilhA+
(que fica em repositório privado).

## Por quê existe

Há histórico documentado de bugs no WebKit (iOS Safari) envolvendo acesso à
câmera especificamente quando um site é instalado na tela inicial e roda em
modo standalone, incluindo casos onde o stream é perdido após navegação. Antes
de investir em calibração de captura biométrica para mobile, é preciso
confirmar se a câmera abre de forma confiável nesse modo específico.

## Como testar

Acesse a página publicada (GitHub Pages) no Safari do iPhone e siga o
protocolo descrito no topo da própria página: teste em aba normal primeiro,
depois adicione à tela de início e teste de novo abrindo pelo ícone.

## Sem dados pessoais

Este repositório é público e contém apenas o protótipo de captura (código),
sem nenhuma captura biométrica real. Os dados de capturas reais ficam no
repositório privado do PilhA+.
