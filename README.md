<h1>-l-i-n-h-a-c-r-u-z-a-d-a-</h1>
<i>Uma vez transformada em ondas eletromagnéticas, a voz pode viajar por cabos telefônicos e se sobrepor a outras, seguindo juntas em uma mensagem que chega até o receptor embaralhada, confusa. 
Quando nossas falas são traduzidas nos bits que viajam pela internet, como elas se sobrepõem, embaralham e confundem?</i>
</br></br></br>
<h2>Como usar?</h2></br>
<p><b>1-</b> Conectar o whatsapp web no navegador</p> <p><b>2-</b> Abrir o <i>console</i> (ctrl + F12)</p> <p><b>3-</b> Copiar e colar o código <i>bot00.js</i></p>

<h2>Sobre</h2>
<b>Esse código é um clone do projeto <a href="https://github.com/bruno222/whatsapp-web-bot">whatsapp-web-bot</a>, com algumas alterações:</b></br>
<p><b>1-</b> Responde qualquer mensagem não lida;</p>
<p><b>2-</b> As mensagens recebidas são armazenadas no vetor <i>lM</i> através da função <i>lM.push(lastMsg)</i>, que as coloca na última posição do vetor. Sempre que uma mensagem é enviada, ela é removida do vetor na operação <i>lM.shift()</i>;</p>
<p><b>3-</b> A saída (mensagem enviada) é sempre o primeiro índice (lM[0]), a menos que o vetor lM esteja vazio. Neste caso, é enviado um poema de Ana Cristina Cesar, embutido no algoritmo a partir da linha <i>213</i>;</p>

<b>Próximas alterações:</b></br>
1- Adicionar áudios.</br>
2- Verificar imagens e selecionar apenas as textuais para repasse.
