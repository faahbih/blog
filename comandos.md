Principais comandos usando linux:

    Install Jekyll and Bundler gems through RubyGems
      ~ $ gem install jekyll bundler

    Create a new Jekyll site at ./myblog
      ~ $ jekyll new myblog

    Show bundle gem (exemplo de tema minima)
      ~ $ bundle show mimina

    Change into your new directory
      ~ $ cd myblog

    Build the site on the preview server
      ~/myblog $ bundle exec jekyll build

    Running
      ~/myblog $ bundle exec jekyll serve or s

    browse to localhost:4000

    Ctrl-C to stop
  
  
  
Principais comandos usando windows antes de rodar o jekyll:

    Primeiro é necessário instalar Chocolatey
    Abra o prompt de comando como administrador e install Chocolatey
        
        @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
        
    Feche o cmd e reabra como administrador
    Instale Ruby
    
        choco install ruby -y
        
    Feche o cmd e abra novamente como administrador
    Instale gem bundler
    
        gem install bundler
        
    Instale jekyll
    
        gem install jekyll
        
    para criar novo projeto
      
        jekyll new myblog
        
    acesse o diretório
    cd myblog:
    
        jekyll serve
        
        
    Build the site on the preview server
      ~/myblog $ bundle exec jekyll build

    Running
      ~/myblog $ bundle exec jekyll serve or s

    browse to localhost:4000

    Ctrl-C to stop
        
        
        
        
    
        


