<h1 id="forgotten">forgotten</h1>

<p>A vim theme inspired by the <a href="https://oblotzky.github.io/sa-oblivion/">Oblivion keycap set</a> by oblotzky (which was inspired by the Oblivion tmTheme by Paolo Borelli).</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr></tr><tr><td align="center"><strong>forgotten-<br />light</strong></td>
<td align="center"><img src="/img/screenshot-forgotten-light.png" alt="screenshot of the forgotten-light vim theme" width="288" /> <img src="/img/screenshot-forgotten-dark.png" alt="screenshot of the forgotten-dark vim theme" width="288" /></td>
<td align="center"><strong>forgotten-<br />dark</strong></td></tr>
</table>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While vim themes can be installed manually (place <a href="https://github.com/nightsense/forgotten/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install forgotten via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/forgotten'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the forgotten theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme forgotten-light</code></li>
  <li><code class="highlighter-rouge">colorscheme forgotten-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows forgotten to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<p>forgotten consists of 16 colours:</p>

<ul>
  <li>8 theme-distinct <strong>base colours</strong></li>
  <li>8 standard <strong>accent colours</strong> (shared by members of the “nightsense theme family”) for syntax highlighting
    <ul>
      <li>hue selection at the scale of 1/12 (30°) colour wheel intervals, followed by 1/12 subinterval adjustments</li>
      <li>value and saturation tuned for light backgrounds, then saturation lowered for dark backgrounds</li>
    </ul>
  </li>
</ul>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base</th>
      <th style="text-align: center">light-background accents</th>
      <th style="text-align: left">dark-background accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/24292b.png" height="24" width="42" /> <code class="highlighter-rouge">24292b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb403a.png" height="24" width="42" /> <code class="highlighter-rouge">eb403a</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/eb6663.png" height="24" width="42" /> <code class="highlighter-rouge">eb6663</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/353c40.png" height="24" width="42" /> <code class="highlighter-rouge">353c40</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb6d13.png" height="24" width="42" /> <code class="highlighter-rouge">eb6d13</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/eb8f4e.png" height="24" width="42" /> <code class="highlighter-rouge">eb8f4e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/464f54.png" height="24" width="42" /> <code class="highlighter-rouge">464f54</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/ebc83b.png" height="24" width="42" /> <code class="highlighter-rouge">ebc83b</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/ebcc4e.png" height="24" width="42" /> <code class="highlighter-rouge">ebcc4e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/6c7275.png" height="24" width="42" /> <code class="highlighter-rouge">6c7275</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/259433.png" height="24" width="42" /> <code class="highlighter-rouge">259433</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/63946a.png" height="24" width="42" /> <code class="highlighter-rouge">63946a</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/889094.png" height="24" width="42" /> <code class="highlighter-rouge">889094</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/009488.png" height="24" width="42" /> <code class="highlighter-rouge">009488</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/56948f.png" height="24" width="42" /> <code class="highlighter-rouge">56948f</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/b0babf.png" height="24" width="42" /> <code class="highlighter-rouge">b0babf</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/308bbf.png" height="24" width="42" /> <code class="highlighter-rouge">308bbf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/609cbf.png" height="24" width="42" /> <code class="highlighter-rouge">609cbf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/d7dde0.png" height="24" width="42" /> <code class="highlighter-rouge">d7dde0</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/8c60bf.png" height="24" width="42" /> <code class="highlighter-rouge">8c60bf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/9e80bf.png" height="24" width="42" /> <code class="highlighter-rouge">9e80bf</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/f5fbff.png" height="24" width="42" /> <code class="highlighter-rouge">f5fbff</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e05e89.png" height="24" width="42" /> <code class="highlighter-rouge">e05e89</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/e082a1.png" height="24" width="42" /> <code class="highlighter-rouge">e082a1</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/eb403a.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/eb6d13.png" height="24" width="42" />
<strong>Orange</strong> is the colour of fire, which serves as a preliminary to many practical activities. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/ebc83b.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/259433.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for positive <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/009488.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign locale type).</p>

<p><img src="http://www.colorhexa.com/308bbf.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/8c60bf.png" height="24" width="42" />
<strong>Purple</strong>, often associated with rare purple dyes historically produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/e05e89.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into existence as one types their names.</p>
