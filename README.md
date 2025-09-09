# Lista de exercicios cobol

Lista de exercicios EM01 da matéria eletiva de cobol com professor Hiro e Takeshi no segundo semestre de 2025.
Esse diretório tem a finalidade de registrar um pouco do meu progresso em cobol!

## Pré requisitos

Todos os programas foram compilados usando "DOSBOXportable" como orientado em sala. Mas existem outros compiladores de arquivos ".cbl" caso queira testar os códigos

## Erros conhecidos
No EX07 tem algum erro de lógica na rotina que calcula a média
```cobol
    CALCULA-MEDIA.
           ADD NOTA1 NOTA2 NOTA3 NOTA4 GIVING SOMA-NOTA.
           DIVIDE SOMA-NOTA BY 4 GIVING WMEDIA.
```
No EX08 existem erros de sintax na rotina "CALCULA-REAJUSTE".