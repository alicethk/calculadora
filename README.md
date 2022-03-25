# calculadora
Atividade 1 e 2 UC13 - Senac2022
A partir de um arquivo de um projeto React-Native pronto denominado "Calculadora", o objetivo era analisar e corrigir, tendo cuidado com o versionamento e criando ramificações (branches) adequadas de modo que não prejudicassem outras funcionalidades que já estavam funcionando adquadamente. 


No projeto inicial havia algumas correções a fazer, as quais já foram atualizadas no App.Js:
Linha 28 troca do sinal + por *
Linha 31 troca do sinal - por /
Linha 69 fechada a View.

Surgiu também o seguinte erro:
FAILURE: Build failed with an exception.
Execution failed for task ':app:stripDebugDebugSymbols'.
> No toolchains found in the NDK toolchains folder for ABI with prefix: arm-linux-androideabi

Foi resolvido excluindo o NDK do Android Studio.

Na atividade 2, foram feitas algumas estilizações e uso do darkMode.

