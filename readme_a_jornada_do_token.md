# 🧠 A Jornada do Token: Do Texto à Matriz

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML5%20|%20TailwindCSS%20|%20Three.js-blue)
![Licença](https://img.shields.io/badge/Licença-MIT-purple)

Um laboratório interativo, visual e altamente didático que desmistifica o funcionamento interno dos Grandes Modelos de Linguagem (LLMs), como o ChatGPT, Gemini e Claude. 

Esta aplicação web foi criada sob a ótica do **Design Instrucional** e do **Ensino Mediado por Tecnologia**, transformando a abstração matemática e estatística das redes neurais em uma experiência cinematográfica e compreensível passo a passo.

---

## 🎯 Objetivo Pedagógico

O ensino de Inteligência Artificial Generativa frequentemente esbarra em uma barreira de abstração (matrizes, hiperplanos, vetores de alta dimensionalidade). O objetivo deste laboratório é **tornar o invisível, visível**. 

Ao clicar no botão "Play", o usuário acompanha o ciclo de vida exato de um *prompt*, entendendo empiricamente que a IA não compreende palavras, mas sim relações geométricas entre números no espaço.

## 🚀 Fluxo de Aprendizagem (Timeline Dinâmica)

O laboratório guia o aluno automaticamente pelas seguintes fases:

1. **A Entrada (Mundo Natural):** O usuário digita um texto (ex: `"O que é IA Generativa?"`).
2. **Tokenização BPE (O Fatiador):** O texto voa pela interface e é fragmentado em sub-palavras (tokens).
3. **Mapeamento de Vocabulário:** As palavras "giram" e se transformam em IDs numéricos puros.
4. **Matriz de Embeddings:** Cada ID busca sua assinatura semântica multivetorial, normalizada em uma matriz bidimensional gerada em tempo real.
5. **Espaço Latente e Atenção (Mundo 3D):** Os vetores são projetados em um ambiente 3D simulado com **Three.js**. Os nós orbitam e se conectam (simulando a relação *Query-Key-Value* do mecanismo de autoatenção).
6. **Decodificação Auto-Regressiva:** O modelo calcula as probabilidades (Logits), projeta os novos IDs e os reverte em linguagem humana (a resposta).

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído para ser leve, rodar diretamente no navegador e não exigir processos complexos de *build*:

* **HTML5 & CSS3:** Estrutura e estilização base.
* **JavaScript (Vanilla):** Controle da linha do tempo assíncrona (Async/Await), manipulação do DOM e lógica de simulação estatística.
* **Tailwind CSS (via CDN):** Para um design UI/UX moderno, responsivo e focado no tema "Dark Mode / Cyberpunk".
* **Three.js (via CDN):** Motor gráfico WebGL utilizado para renderizar a nuvem de partículas e a conexão dos nós no hiperespaço vetorial.

## 🖥️ Como Executar o Projeto

Como o projeto não possui dependências de backend (Node.js, Python, etc.), a execução é imediata:

1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/a-jornada-do-token.git
   ```
2. Navegue até a pasta do projeto.
3. Abra o arquivo `index.html` em qualquer navegador web moderno (Chrome, Edge, Firefox, Safari).
   * *Dica: Você também pode usar a extensão "Live Server" do VS Code para uma melhor experiência de desenvolvimento.*

## 🤝 Contribuindo para o Ensino

Este é um projeto educacional de código aberto. Se você é educador, desenvolvedor ou entusiasta da IA, sinta-se à vontade para contribuir:

1. Faça um Fork do projeto.
2. Crie uma *Branch* para sua modificação (`git checkout -b feature/NovaAnimacaoDidatica`).
3. Faça o *Commit* de suas alterações (`git commit -m 'Add: nova explicação sobre Softmax'`).
4. Faça o *Push* para a Branch (`git push origin feature/NovaAnimacaoDidatica`).
5. Abra um *Pull Request*.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes. O uso em salas de aula, palestras e workshops é não apenas permitido, mas fortemente encorajado! 👨‍🏫👩‍🏫