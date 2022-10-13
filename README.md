

<h2>Estrutura de Pastas:</h2><br>
<pre>
    root
    ├──── README.md
    │ ├── index.html
    │ ├── pages
    │ │ └──
    │ ├── images
    │ │ ├── audio
    │ │ ├── images
    │ │ └── videos
    │ ├── src
    │ │ └── style.css
    │ ├── samples
    │ │ └──test
    │ │ └──
    └──── LICENSE
</pre>

<h2>Semântica em <code>HTML</code>:</h2><br>
<img src="/images/tags-semanticas.png" alt="imagem representando a estrutura das tags"><br>
<p>
    Exemplos de algumas tags não semânticas: <br>
    <kbd style="color:black">&lt;span&gt;&lt;&#47;span&gt;</kbd><br>
    <kbd style="color:black">&lt;div&gt;&lt;&#47;div&gt;</kbd><br>
    <kbd style="color:black">&lt;b&gt;&lt;&#47;b&gt;</kbd><br>
    <kbd style="color:black">&lt;i&gt;&lt;&#47;i&gt;</kbd><br>

</p>

<p>
    Exemplos de algumas tags semânticas: <br>
    <kbd style="color:black">&lt;strong&gt;&lt;&#47;strong&gt;</kbd><br>
    <kbd style="color:black">&lt;em&gt;&lt;&#47;em&gt;</kbd><br>
    <kbd style="color:black">&lt;article&gt;&lt;&#47;article&gt;</kbd><br>
    <kbd style="color:black">&lt;aside&gt;&lt;&#47;aside&gt;</kbd><br>
    <kbd style="color:black">&lt;details&gt;&lt;&#47;details&gt;</kbd><br>
    <kbd style="color:black">&lt;figcaption&gt;&lt;&#47;figcaption&gt;</kbd><br>
    <kbd style="color:black">&lt;figure&gt;&lt;&#47;figure&gt;</kbd><br>
    <kbd style="color:black">&lt;footer&gt;&lt;&#47;footer&gt;</kbd><br>
    <kbd style="color:black">&lt;header&gt;&lt;&#47;header&gt;</kbd><br>
    <kbd style="color:black">&lt;main&gt;&lt;&#47;main&gt;</kbd><br>
    <kbd style="color:black">&lt;mark&gt;&lt;&#47;mark&gt;</kbd><br>
    <kbd style="color:black">&lt;nav&gt;&lt;&#47;nav&gt;</kbd><br>
    <kbd style="color:black">&lt;section&gt;&lt;&#47;section&gt;</kbd><br>
    <kbd style="color:black">&lt;summar&gt;&lt;&#47;summar&gt;</kbd><br>
    <kbd style="color:black">&lt;time&gt;&lt;&#47;time&gt;</kbd><br>

</p>

<h2>Micro Dados:</h2>
<p>
    Parte do padrão HTML. <br>
    Mecanismos de pesquisa e rastreadores consomem os dados com mais eficiência. <br>
    Servem para aninhar metadados em conteúdo existente em páginas WEB. (Microdata, RDFa, JSON - LD)
</p>

<h2>Microdata</h2>

<div itemscope itemtype="https://schema.org/SoftwareApplication">
    <span itemprop="name">
        Angry Birds
    </span>
    -REQUIRES
    <span itemprop="operatingSystem">
        ANDROID
    </span>
    <br>
    <link itemprop="aplicationCategory" href="https://schema.org/GameApplication">

    <div itemprop="aggregateRating" itemscope itemtype="https://schema.org/AggregateRating">
        Pontuação: 
        <span itemprop="ratingValue">
            4.6
        </span> (
        
        <span itemprop="ratingCount">
            8864
        </span> avaliações)
    </div>

    <div itemprop="offers" itemscope itemtype="https://schema.org/Offer">
        Preço $
        <span itemprop="price">
            R$ 10.00
        </span>
        <meta itemprop="priceCurrency" content="USD"/>
    </div>
</div>

<h2>RDFa</h2>

        <!DOCTYPE html>
        <html lang="pt">
            <head>
                <title>Exemplo de documento</title>
            </head>
    
            <body vocab="http://texpersts.com.br/blog">
                <p typeof="Blog">
                    Bem vindo ao <a propety="url" href="http://texpersts.com.br/blog">Blog da T.EX</a>.
                </p>
            </body>
        </html>

<h2>JSON-LD (Link Data)</h2>


<html>
<head>
   <title>Bolo de Café</title>
 <script type="aplication/ld+json">
   {
     "@context": "https://schema.org",
      "@type": "Recipe",
      "name": "Bolo de café",
      "autor": {
      "@type": "Person",
      "name": "Fernando M. Sousa",
     },
     {
        "datePublished": "2018-03-10",
        "description": "Este bolo é perfeito para a sua festa.",
        "prepTime": "PT20M"
        }
  </script>
 </head>
 <body>
    <h2>Bolo de Café</h2>
       <p>
          <i>Por Fernando M. Sousa, 10-06-2022</i>
       </p>
       <p>
          Este bolo é perfeito para a sua festa.
        </p>
        <p>
          Preparação: 20 minutos
        </p>
      </body>
      </html>


        <h2>Cores</h2>

       <h3>R G B</h3>
       <P>Red(0-255) | Green (0-255) | Blue (0-255)</P>
       <p>rgb(0,0,0) = preto</p>
       <p>rgb(255,255,255) = branco</p>
       <p>rgb(255,0,0) = vermelho</p>
       <p>rgb(0,255,0) = verde</p>
       <p>rgb(0,0,255) = azul</p>

       <h3>R G B a</h3>
       <P>Red(0-255) | Green (0-255) | Blue (0-255) | Transparência(0-1)</P>
       <p>rgb(255,255,255, 0.8)</p>

       <h3>H S L (hue - tonalidade, saturation - saturação, lightness - luminosidade)</h3>

       <P>hue(0-360) | saturation (%) | lightness (%)</P>
       <p>rgb(255,255,255, 0.8)</p>

       <h3>Hexadecimal</h3>

       <p>0123456789ABCDEF</p>
       <p>#ffffff</p>





















        







