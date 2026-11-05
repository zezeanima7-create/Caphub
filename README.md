# CapHub Studio

Editor gratuito de animações 2D e vídeos com formas geométricas e Countryballs.

## Recursos do Studio 0.2

- Editor visual responsivo para celular Android e computador.
- Formas: círculo, quadrado, triângulo e estrela.
- Countryballs com bandeiras selecionáveis.
- Texto, imagens importadas e fundo configurável.
- Projetos com várias cenas: adicionar, duplicar e excluir.
- Camadas por cena, seleção e posicionamento direto no palco.
- Keyframes para posição X/Y, tamanho, rotação e opacidade, com interpolação entre pontos.
- Transições de desvanecimento e deslizamento sobre a cena anterior (além de corte).
- Transições de entrada de cena: corte, desvanecer e deslizar.
- Importação de faixas de áudio, ajuste do ponto de início e volume; áudio sincronizado na pré-visualização e na exportação quando suportado.
- Pré-visualização, salvamento automático local e exportação/importação JSON com mídias incorporadas.
- Exportação de frame PNG e vídeo WebM com áudio quando o navegador oferece suporte a MediaRecorder e captura de áudio.

## Como usar

Abra `index.html` em um navegador moderno. Não precisa de instalação, build, conta ou dependência externa. O repositório também contém um fluxo do GitHub Actions para publicar o site no GitHub Pages quando a publicação estiver habilitada nas configurações do repositório.

1. Adicione objetos pela Biblioteca.
2. Arraste um objeto no palco para posicioná-lo.
3. Mova o controle de tempo e ajuste posição X/Y, tamanho, rotação ou opacidade.
4. Clique em **Keyframe** para registrar a animação naquele instante.
5. Crie outras cenas e escolha uma transição de entrada.
6. Importe áudio, ajuste início e volume e use **Reproduzir** para conferir.
7. Baixe o projeto JSON para guardar uma cópia completa, ou exporte o vídeo WebM.

## Limitações

- A exportação de vídeo é WebM; MP4 ainda não está implementado.
- O resultado da gravação depende do suporte do navegador e pode variar entre aparelhos.
- O salvamento automático usa o armazenamento do navegador. Projetos com arquivos de mídia grandes podem ultrapassar o limite; nesse caso, use a exportação JSON.
- As transições implementadas são de entrada de cena. Edição avançada de áudio, efeitos visuais e sincronização detalhada de múltiplas faixas ainda podem ser adicionados.

## Licença

Projeto em desenvolvimento.
