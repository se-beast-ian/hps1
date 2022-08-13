<p align="center">
  <img width="256" height="256" src="https://cdn001.tintin.com/public/tintin/img/static/captain-haddock/captain-haddock_v2.jpg">
</p>

<h6 align="center">Captain Haddock © Hergé / Moulinsart 2022</h1>

### HPS1

A collection of solemn utterances ancestring to Captain Haddock (<a href="https://www.tintin.com/">Tin Tin<a/>)  ... conveniently packaged as your bash shell prompt. <br>
So convenient in fact, that it will change on each prompt. This way when something doesn't work right, you have a curse word ready!

### Why the need for this

Computer code and cursing are intricately related and inseparable, especially when things go wrong. Not if, when. Cursing is frowned upon - in the best of cases -
so why not do it in style ?

### Which style?

  Code fails to compile? <b>Thousands of thundering typhoons! </b> <br>
  Program crashes? <b> Millions and billions of blue blistering barnacles </b> <br>
  rm -rvf / as sudo? <b> Dictatorial duck-billed diplodocus </b> <br><br>
  Demo: https://youtu.be/4L3NLH-bR5Y <br>


### Installation

  <ul>
    <li> Clone the repository and copy <b>haddocks.sh</b> and <b>haddocks.txt</b> into your home directory </li>
    <li> Copy/Paste <br>

  
    if [ -f ~/haddocks.sh ]; then
        if [ -f ~/haddocks.txt ]; then
            PS1='$(~/haddocks.sh)'
        else
            PS1="Haddocks_not_on$ "
        fi
    fi

into your ~/.bashrc config


    </li>

  </ul>


### Project roadmap

At present, the project is in its raw phase. Fo'shurr i have to make the installation process much better. It's my sunday morning fun project. Don't expect too much of it, but i hope it makes you giggle a bit.
