### Enunciado:

Crie uma fotografia publicitária de um produto ou alimento de sua escolha.

Sugestões
- Fotografia gastronômica para um restaurante
- Fotografia de produto para uma campanha
- Imagem editorial para uma marca
- Conteúdo publicitário para redes sociais

### Escolhas e estapas:

Escolha: Fotografia gastronômica para um restaurante
Tecnica a ser utilizada: JSON Remix

Passos:
- Extraímos as características da imagem para uma estrutura.
- Escolhemos o que deve permanecer.
- Modificamos apenas os campos desejados.
- Reutilizamos o JSON na próxima geração.

### Execução:

#### Passo 1 - Escolha e extração

Escolha da imagem: Escolha de uma imagem de minitorta de morango retirada do site de imagens gratuitas Pixabay.

Link da imagem (Fotografia de NoName_13) : https://pixabay.com/pt/photos/torta-de-morango-caf%C3%A9-morango-2613073/

Prompt de extração (Slide de aula):

Crie um perfil de contexto JSON profundamente detalhado e avançado para esta imagem. Este JSON deve ser estruturado para capturar todos os dados visuais, espaciais, semânticos e atmosféricos interpretáveis, adequado para manipulação ou reconstrução de imagem de alta fidelidade. Seu objetivo é gerar uma representação legível por máquina que encapsule toda a cena com nuance, hierarquia e precisão. Inclua o seguinte na saída JSON:  
1. **objetos**: Liste cada objeto identificável. Para cada um, inclua seu rótulo, descrição (cor, textura, material), posição, tamanho relativo e relações com outros objetos. 
2. **ambiente**: Descreva o cenário, hora do dia, iluminação (fonte, direção, cor), clima e fundo. 
3. **pessoas** (se houver): Detalhe a idade/gênero estimados de cada pessoa, expressão, pose, roupas e atividade. 
4. **composição**: Note o ângulo da câmera, enquadramento, profundidade focal, equilíbrio visual e paleta de cores. 
5. **simbolismo_e_história**: Descreva qualquer narrativa implícita, pistas emocionais ou elementos simbólicos. 
6. **metadados**: Inferir o estilo da imagem (por exemplo, foto, ilustração) e potenciais influências artísticas.  

Saída do JSON como um único objeto estruturado. Priorize precisão e profundidade para servir como um blueprint abrangente para modelos generativos, garantindo que todos os dados posicionais e composicionais possam ser preservados durante trocas de objetos ou ambientes.

Prompt utilizado no Gemini (3.6 Flash), resultado obitido no arquivo "imagemTorta.json"

#### Passo 2 - Escolha e realização das modificações:

Decidido a mudar o sabor da torta de morango para chocolate.

Foi decidido usar o site Design Arena para geração da nova imagem, para ver os resultados de mais de uma unica IA e para manter a lógica utilizada na aula.

Prompt utilizado: 

Mantenha todas as características descritas no JSON em anexo, mas troque a torta de morango por uma torta de chocolate. 

#### Passo 3 - Geração da nova imagem:

O design arena gerou 4 imagens com IAs diferentes, em sua maioria não se aproximam tanto da imagem inicial e apenas a primeira pode ser baixada (foi adicionada nos arquivos do projeto):

1. Muse image: A torta apareceu maior e cortada
2. GPT-image-1.5: Adicionou variso elemento e aumentou a torta
3. Krea 2 Medium: tornou a torta em apenas uma fatia
4. MAI-image-2.6: A imagem mais distante, adicionando pessoa humana e diversos ementos adicionais de cenário

Não satisfeito com o resultado geral foi utilizado o gemini (Flash 3.6), na mesma conversa da geração do JSON, para a criação de uma nova imagem, com o seguinte prompt:

Mantenha todas as características descritas no JSON gerado, mas troque a torta de morango por uma torta de chocolate. 

O resultado foi muito proximo da imagem original, sendo a mais fiel a proposta de manter uma mesma imagem trocando apenas alguns elementos. 