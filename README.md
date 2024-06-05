### MenuBackups
A classe `MenuBackups` é responsável por gerar o menu de gerenciamento de backups e tratar as entradas do usuário.

#### Métodos Implementados:
- `void criarBackup()`: Gera um backup de todos os arquivos utilizando a função `void compacta()` descrita abaixo.
- `void restaurarBackup()`: Lista para o usuário todos os arquivos de backup presentes atualmente na pasta backup e permite a seleção de um deles para ser restaurado utilizando a função `void descompacta(backup: String)` descrita abaixo.
- `void removerBackup()`: Lista para o usuário todos os arquivos de backup presentes atualmente na pasta backup e permite a seleção de um deles para ser removido.

### ArquivoBackup
A classe `ArquivoBackup` é responsável pelo gerenciamento da compactação e descompactação dos arquivos solicitados.

#### Métodos Implementados:
- `void compacta()`: Lista todos os arquivos presentes na pasta `dados`, gera um array de bytes através de um dicionário e por fim salva na pasta backup com nome de acordo com data e hora atual.
- `void descompacta(backup: String)`: Recebe o nome do arquivo de backup, decodifica e reescreve nos arquivos da pasta `dados` de acordo com o nome do arquivo.

### Questionário
- Há uma rotina de compactação usando o algoritmo LZW para fazer backup dos arquivos? Sim
- Há uma rotina de descompactação usando o algoritmo LZW para recuperação dos arquivos? Sim
- O usuário pode escolher a versão a recuperar? Sim
- Qual foi a taxa de compressão alcançada por esse backup? Aproximadamente 80% de acordo com o cálculo feito
https://github.com/PedroAugusto1907/tp3/blob/02d988fc47feac7015dff05ea27fc377f94a73c1/arquivos/ArquivoBackup.java#L48
- O trabalho está funcionando corretamente? Sim
- O trabalho está completo? Sim
- O trabalho é original e não a cópia de um trabalho de um colega? Sim
