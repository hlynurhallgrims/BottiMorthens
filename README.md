<p align="center"> 
<img src="https://github.com/hlynurhallgrims/BottiMorthens/blob/master/img/Botti_profile.png">
</p>

<h1 align="center">Botti Morthens</h1>
<p><strong>Eins lags LSTM tauganet sem er búið að liggja yfir Twitteraðgangi Bubba Morthens</strong></p>
<p align="left">Botti Morthens er tauganet þjálfað á tístum Bubba Morthens. Tauganetið samanstendur af einu <em>LSTM (long short-term memory)</em> lagi og svo 
<em>dense classifier</em> og <em>softmax</em> yfir alla mögulega stafi. Tauganetið býr til sínar eigin textarunur sem svo birtast á Twitter.</p>

<p>Botti Morthens er samstarfsverkefni <a href="https://github.com/Eikonomics">@Eikonomics</a> og <a href="https://github.com/hlynurhallgrims">@hlynurhallgrims</a>
og forritað í R. Eiki og Hlynur nota venjulega líkön í praktískari (en minna spennandi) hluti heldur en að dæla út skrítnum Bubba tístum, og er þetta 
lærdómsferli í þeim skilningi. Sem stendur byggir Botti Morthens alfarið á kafla 8 í bókinni <em><a href="https://www.manning.com/books/deep-learning-with-r">Deep Learning with R</a></em>
sem við mælum heilshugar með. Öllum er frjálst að nota kóðann í þessu repo-i á hvern þann hátt sem þeim sýnist, í samræmi við það leyfi sem Francois Chollet og JJ Allaire,
höfundar Deep Learning with R, setja á kóðabútana í 8. kafla Deep Learning with R.</p>

<h2>Hvað er á döfinni hjá Botta Morthens</h2>

- Prufa sig áfram með meira granularity í <em>softmax entropy</em>
- Athuga hvort 1D convnet sé ef til vill betra
- Skoða hvort við náum að setja inn greinarmerki í núverandi mynd.
- Eitthvað annað sem við ættum að skoða? Endilega láttu okkur vita.

## LICENSE

MIT License

Copyright (c) 2017 François Chollet  
Copyright (c) 2017 J.J. Allaire

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
