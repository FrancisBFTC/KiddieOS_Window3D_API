# KiddieOS_API_1.2.6

Arquivo de alternância de resoluções gráficas utilizando VESA. Através desta LIB é possível encontrar e utilizar resoluções altas.

## Chamando um modo especial (Cores ARGB ou RGB)

* 1 - Inclua o arquivo vesa inserindo: #include "VESA.lib"
* 2 - Determine as variáveis "BPP_Required", "ReX_Required" e "ReY_Required", usando instrução MOV ou definindo estáticamente.
* 3 - Execute a rotina "Set_Video_Mode" inserindo: CALL Set_Video_Mode

**Nota**: o número de modo especial pode ser diferente em cada máquina ou na máquina real. 

## Chamando um modo padrão (Apenas RGB)

* 1 - Observe nos comentários a partir da sessão "Lista PADRÃO de Modos VESA" e encontre sua resolução.
* 2 - Após encontrar o número do modo desejado, mova para CX e insira CX na variável "GUI.Video_Mode"
* 3 - Capture informações do modo gráfico utilizando: CALL VBE_Info_Mode
* 4 - Inicialize o modo gráfico utilizando: CALL VBE_Init_Mode
* 5 - Salve informações de vídeo principais utilizando: CALL VESA.GetInfo

**Nota** : As informações de vídeo principais estão na 1ª estrutura a partir da variável "GUI" nas primeiras 5 variáveis.

[Clique aqui e aprenda a criar SOs no Curso D.S.O.S](https://www.youtube.com/playlist?list=PLsoiO2Be-2z8BfsSkspJfDiuKeC9-LSca)

Veja as atualizações e o progresso do projeto logo abaixo:

# [Versão 1.0.0](https://github.com/FrancisBFTC/KiddieOS_Window3D_API)

# [Versão 1.1.0](https://github.com/FrancisBFTC/KiddieOS_Window3D_API/tree/Win3dmov.lib-1.1.0)

# [Versão 1.2.0](https://github.com/FrancisBFTC/KiddieOS_Window3D_API/tree/Win3dmov.lib-1.2.0)

# [Versão 1.2.1](https://github.com/FrancisBFTC/KiddieOS_Window3D_API/tree/win3dmov_lib_serial_1.2.1)

# [Versão 1.2.6](https://github.com/FrancisBFTC/KiddieOS_Window3D_API/tree/graphics_lib_1.2.6)

