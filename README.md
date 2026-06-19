# Prompt-neural-video
 
**Método criado por Ronan (Diretor do Comedy Left TV), documentado pelo Gabinete P2.**

## 1. O Problema
Quando você pede para uma IA de vídeo gerar uma cena com personagem, ela frequentemente:
- Narra a ação em vez de animar o boneco ("Era uma vez um homem que...").
- Descreve a cena em vez de simplesmente executar a ação.
- Perde a consistência da voz e da personalidade do personagem.

Resultado: vídeos genéricos, sem alma e com "narrador fantasma".

## 2. A Solução (O Protocolo Neural)
Separar a **ALMA** do personagem da **IMAGEM**. A IA não precisa "imaginar" a aparência. Ela precisa saber apenas **COMO FALAR** e **O QUE FAZER**.

O prompt é dividido em 3 partes obrigatórias (e uma quarta opcional).

## 3. A Estrutura do Prompt (Template Zerado)

### 3.1 Regra Neural (A Alma)
Define **apenas** a voz e a personalidade. Não descreva roupa, cor ou cenário. Isso já vem na imagem de referência.

**Formato:**

TEMPLATE ZERADO – PROTOCOLO NEURAL<p>

Regra Neural:<p>
[PERSONAGEM] fala diretamente, sem narrador, com voz [TOM DE VOZ]. Respeitar a lógica e a minutagem da [fala].<p>

[fala]:<p>
0-Xs: [Personagem diz: "Fala." Ação breve].<p>
X-Ys: [Personagem diz: "Fala." Ação breve].<p>
Y-Zs: [Personagem diz: "Fala." Ação breve].<p>

Tela Preta Final: Texto: "[Frase de efeito]".<p>

EXEMPLO PREENCHIDO (TONY TORTÃO):<p>

Regra Neural:<p>
Tony Tortão fala diretamente, sem narrador, com voz extremamente fina e motivada. Respeitar a lógica e a minutagem.

[fala]:<p>
  0-5s: Tony está deitado. Uma coxa de frango flutua até ele.<p>
  5-10s: Tony diz: "Tony... vai comer." Ele morde o frango.<p>
  10-15s: A barriga de Tony brilha forte. Ele dança e diz: "Come, come, come... Tony tá fortão!"<p>
  15-17s: Tony boceja e dorme. Barriga brilha.<p>

  Tela Preta Final: Texto: "Malhar, comer, brilhar, dormir."<p>
