# Ocean Mod (Forge 1.21 - loader 51.0.22)

## Como compilar (gerar o .jar)
1. Instale o JDK 21.
2. Baixe o MDK do Forge 1.21-51.0.22 em https://files.minecraftforge.net (botao "Mdk").
3. Extraia o MDK e COPIE para dentro dele: a pasta `src/` e o arquivo `build.gradle` deste projeto (substituindo os do MDK).
4. No terminal da pasta: `gradlew build` (Windows) ou `./gradlew build`.
5. O mod fica em `build/libs/oceanmod-1.0.0.jar` -> coloque na pasta `mods` do seu mod-pack no TLauncher.

## Como jogar
- Leme de Barco (aba Ferramentas): construa o casco com qualquer bloco, qualquer tamanho (ate 1500 blocos),
  ponha o leme em cima e clique direito -> vira um barco. A proa aponta para o SUL ao montar.
- Motores 5/10/25/50/75/100 HP: segure o motor e clique direito no barco. Trocar devolve o antigo.
- Clique direito (mao vazia) para pilotar: W/S acelera/re, A/D vira. Barco maior = mais pesado = motor precisa ser mais forte.
- Agachar + clique direito: desmonta o barco de volta em blocos.
- Ondas: o barco sobe/desce e inclina nas ondas. Chuva = ondas medias, tempestade com trovao = ondas enormes (~2,5 blocos).
- Evite montar barcos "colados" em terra (areia/terra/pedra natural sao ignoradas, mas outros blocos conectados entram).

## Jeito facil (sem instalar nada): compilar pelo GitHub
1. Crie uma conta gratis em github.com e um repositorio novo (botao "New").
2. Envie TODO o conteudo desta pasta (inclusive a pasta oculta `.github`) para o repositorio
   ("Add file" > "Upload files"; arraste tudo).
3. Abra a aba "Actions", espere o "Build mod" ficar verde (uns 3-5 min).
4. Clique na execucao > baixe "oceanmod-jar" (vem em zip) > extraia o .jar > ponha na pasta `mods`.
