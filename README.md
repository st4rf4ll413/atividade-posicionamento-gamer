# Laboratório Prático: Posicionamento CSS & Z-Index
## Tema: Lobby de Campeões (Arena RPG)

Arquivo base inicial e enxuto. O CSS contém apenas cores, fontes e tamanhos básicos de texto.

---

### 📂 Arquivos:
- `index.html`: Estrutura HTML semântica básica.
- `css/styles.css`: CSS inicial (sem posicionamento aplicado).
- `img/`: Imagens dos três campeões (`mago.svg`, `robo.svg`, `ninja.svg`).

---

### 🎯 Missão do Aluno:
Abra o arquivo `css/styles.css` e aplique as regras de posicionamento:

1. **Header Fixo com Rolagem:**
   - No `.hud-superior`, use `position: sticky`, `top: 0` e `z-index`.
2. **Referência do Card:**
   - No `.card-campeao`, use `position: relative`.
3. **Badges e Tags sobrepostas:**
   - Na `.badge-raridade` e `.tag-status`, use `position: absolute`, coordenadas (`top`, `right`, `left`) e `z-index` para sobrepor a imagem do campeão.
4. **Botão de Chat Flutuante:**
   - No `.btn-chat-squad`, use `position: fixed`, coordenadas (`bottom`, `right`) e `z-index` para mantê-lo fixo no canto inferior da janela.
