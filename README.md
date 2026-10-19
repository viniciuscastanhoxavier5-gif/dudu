# DUDU — Training Sandbox (C++ / Visual Studio)

Projeto de demonstração para Windows com menu preto/roxo e alvos inteiramente simulados na própria janela. **Não se conecta ao Roblox nem a outros processos**, não injeta DLLs e não lê/escreve memória de jogos.

## Recursos
- Menu arrastável pela barra superior do painel.
- F6 mostra/oculta o menu.
- ESC fecha o programa.
- ESP de teste: caixas e rótulos nos alvos simulados.
- Aim assist de teste: retículo se move suavemente em direção ao alvo simulado mais próximo dentro do FOV.
- FOV ajustável com slider.
- Clique na área de treino para reposicionar o retículo.

## Compilar no Visual Studio 2022
1. Instale a carga de trabalho **Desenvolvimento para desktop com C++**.
2. Clone ou baixe este repositório como ZIP.
3. Abra `DUDU.sln`.
4. Selecione **Release** e **x64**.
5. Use **Compilar > Compilar Solução** (Ctrl+Shift+B).
6. Execute com **Depurar > Iniciar sem depuração** (Ctrl+F5).

O executável normalmente ficará em `DUDU\x64\Release\DUDU.exe`. Usa apenas Win32/GDI do Windows SDK.
