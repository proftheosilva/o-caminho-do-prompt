# ðŸ§  A Jornada do Token: Do Texto Ã  Matriz

![Status do Projeto](https://img.shields.io/badge/Status-ConcluÃ­do-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML5%20|%20TailwindCSS%20|%20Three.js-blue)
![LicenÃ§a](https://img.shields.io/badge/LicenÃ§a-MIT-purple)

Um laboratÃ³rio interativo, visual e altamente didÃ¡tico que desmistifica o funcionamento interno dos Grandes Modelos de Linguagem (LLMs), como o ChatGPT, Gemini e Claude. 

Esta aplicaÃ§Ã£o web foi criada sob a Ã³tica do **Design Instrucional** e do **Ensino Mediado por Tecnologia**, transformando a abstraÃ§Ã£o matemÃ¡tica e estatÃ­stica das redes neurais em uma experiÃªncia cinematogrÃ¡fica e compreensÃ­vel passo a passo.

---

## ðŸŽ¯ Objetivo PedagÃ³gico

O ensino de InteligÃªncia Artificial Generativa frequentemente esbarra em uma barreira de abstraÃ§Ã£o (matrizes, hiperplanos, vetores de alta dimensionalidade). O objetivo deste laboratÃ³rio Ã© **tornar o invisÃ­vel, visÃ­vel**. 

Ao clicar no botÃ£o "Play", o usuÃ¡rio acompanha o ciclo de vida exato de um *prompt*, entendendo empiricamente que a IA nÃ£o compreende palavras, mas sim relaÃ§Ãµes geomÃ©tricas entre nÃºmeros no espaÃ§o.

## ðŸš€ Fluxo de Aprendizagem (Timeline DinÃ¢mica)

O laboratÃ³rio guia o aluno automaticamente pelas seguintes fases:

1. **A Entrada (Mundo Natural):** O usuÃ¡rio digita um texto (ex: `"O que Ã© IA Generativa?"`).
2. **TokenizaÃ§Ã£o BPE (O Fatiador):** O texto voa pela interface e Ã© fragmentado em sub-palavras (tokens).
3. **Mapeamento de VocabulÃ¡rio:** As palavras "giram" e se transformam em IDs numÃ©ricos puros.
4. **Matriz de Embeddings:** Cada ID busca sua assinatura semÃ¢ntica multivetorial, normalizada em uma matriz bidimensional gerada em tempo real.
5. **EspaÃ§o Latente e AtenÃ§Ã£o (Mundo 3D):** Os vetores sÃ£o projetados em um ambiente 3D simulado com **Three.js**. Os nÃ³s orbitam e se conectam (simulando a relaÃ§Ã£o *Query-Key-Value* do mecanismo de autoatenÃ§Ã£o).
6. **DecodificaÃ§Ã£o Auto-Regressiva:** O modelo calcula as probabilidades (Logits), projeta os novos IDs e os reverte em linguagem humana (a resposta).

## ðŸ› ï¸ Tecnologias Utilizadas

Este projeto foi construÃ­do para ser leve, rodar diretamente no navegador e nÃ£o exigir processos complexos de *build*:

* **HTML5 & CSS3:** Estrutura e estilizaÃ§Ã£o base.
* **JavaScript (Vanilla):** Controle da linha do tempo assÃ­ncrona (Async/Await), manipulaÃ§Ã£o do DOM e lÃ³gica de simulaÃ§Ã£o estatÃ­stica.
* **Tailwind CSS (via CDN):** Para um design UI/UX moderno, responsivo e focado no tema "Dark Mode / Cyberpunk".
* **Three.js (via CDN):** Motor grÃ¡fico WebGL utilizado para renderizar a nuvem de partÃ­culas e a conexÃ£o dos nÃ³s no hiperespaÃ§o vetorial.

## ðŸ–¥ï¸ Como Executar o Projeto

Como o projeto nÃ£o possui dependÃªncias de backend (Node.js, Python, etc.), a execuÃ§Ã£o Ã© imediata:

1. Clone este repositÃ³rio:
   ```bash
   git clone https://github.com/SEU_USUARIO/a-jornada-do-token.git
   ```
2. Navegue atÃ© a pasta do projeto.
3. Abra o arquivo `index.html` em qualquer navegador web moderno (Chrome, Edge, Firefox, Safari).
   * *Dica: VocÃª tambÃ©m pode usar a extensÃ£o "Live Server" do VS Code para uma melhor experiÃªncia de desenvolvimento.*

## ðŸ¤ Contribuindo para o Ensino

Este Ã© um projeto educacional de cÃ³digo aberto. Se vocÃª Ã© educador, desenvolvedor ou entusiasta da IA, sinta-se Ã  vontade para contribuir:

1. FaÃ§a um Fork do projeto.
2. Crie uma *Branch* para sua modificaÃ§Ã£o (`git checkout -b feature/NovaAnimacaoDidatica`).
3. FaÃ§a o *Commit* de suas alteraÃ§Ãµes (`git commit -m 'Add: nova explicaÃ§Ã£o sobre Softmax'`).
4. FaÃ§a o *Push* para a Branch (`git push origin feature/NovaAnimacaoDidatica`).
5. Abra um *Pull Request*.

## ðŸ“„ LicenÃ§a

Este projeto estÃ¡ sob a licenÃ§a MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes. O uso em salas de aula, palestras e workshops Ã© nÃ£o apenas permitido, mas fortemente encorajado! ðŸ‘¨â€ðŸ«ðŸ‘©â€ðŸ«
