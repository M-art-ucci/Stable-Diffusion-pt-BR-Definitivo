<h1 align="center">
  <a href="https://github.com/M-art-ucci">
    <img src="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/blob/main/Assets/logo%20ouro%20veludo.png" alt="Logo" width="125" height="125">
  </a>
  <a href="https://discord.com/invite/9ZFdQH5YP6">
    <img src="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/blob/main/Assets/logo%20discord%20copy.png" alt="Logo" width="125" height="125">
</h1>
<a href="https://tecnoblog.net/responde/como-usar-o-github-guia-para-iniciantes/">Como usar Github?</a>

# Guia definitivo de instalação do Stable Diffusion
  	
  <a href="[b27da3676739813c35aa2d6aac4bd6d1326a2a7b](https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/commit/b27da3676739813c35aa2d6aac4bd6d1326a2a7b)](https://img.shields.io/badge/%C3%BAltima%20modifica%C3%A7%C3%A3o-12%2F11%2F2022-green"><img src="https://img.shields.io/badge/%C3%BAltima%20modifica%C3%A7%C3%A3o-12%2F11%2F2022-green">

### Com [Interface do AUTOMATIC1111](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
<div align="left"> Localização oficial <a href="https://github.com/M-art-ucci">M-art-ucci</a>
</div>

---

<div align="center">

- [x] Soluções para tela preta
- [x] Passo a passo de instalação com imagens/gifs
- [ ] Opções para quem tem de 4GB a 6GB de VRAM
- [ ] [Todos os problemas estão resolvidos](https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/issues)
  <br />
  <br />
  
  <b>Avisos</b>
  
  <a href="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/issues">Reportar bugs</a>
  ·
  <a href="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/pulls">Perguntas diversas</a>
</div>

<div align="center">
<br />

[![Feito com ♥ por M-art-ucci](https://img.shields.io/badge/Feito%20com%20%E2%99%A5%20por-M--art--ucci-red)](https://github.com/M-art-ucci)
[![PRs welcome!](https://img.shields.io/badge/PRs-bem--vindos-orange)](https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/pulls)
[![licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-green)](LICENSE)

</div>

<div align="left"> Obs¹: este guia sempre estará mais atualizado que os vídeos
</div>

---

 <div>
 <h3><details open><summary><b>Pré-requisitos</b></summary>
     <blockquote><details><summary>
     Windows ou Linux
     </summary>
        <blockquote>
        Windows 10/11
        </blockquote>
        <blockquote>
        Linux
        </blockquote></details>
  <details closed><summary>Placas de vídeo</summary>
    <blockquote><details><summary>Nvidia com mais de 6GB de VRAM</summary>
      <blockquote>
      Cada Placa
      </blockquote></details>
  <details closed><summary>Nvidia com 4GB a 6GB de VRAM</summary>
    <blockquote>
    Cada Placa
    </blockquote></details>
  </blockquote></details>
  <details closed><summary>Python 3.10.7</summary>
    <blockquote>
    <a href="https://www.python.org/ftp/python/3.10.6/python-3.10.6-amd64.exe">Instalador (64-bit)</a><sup>ainda não instalar</sup> 
    </blockquote></details>
  <details closed><summary>Git</summary>
    <blockquote>
    <a href="https://github.com/git-for-windows/git/releases/download/v2.38.1.windows.1/Git-2.38.1-64-bit.exe">Instalador (64-bit)</a><sup>ainda não instalar</sup>
    </blockquote></details>
  <details closed><summary>Dependências</summary>
    <blockquote>
    <a href="https://drive.google.com/file/d/1AYUYAQ8j5oeRLF1-grme_qMxt-qALeJ7/view">Google Drive Martucci</a>
    <details closed><summary>Backups</summary>
     <blockquote>
     <a href="https://drive.google.com/drive/folders/1nsKKMCb-OA2MqKDdjU4yAyI8GBWHWiFs">Drive do Aitrepreneur</a>
     </blockquote>
     <blockquote>
     <a href="https://mega.nz/file/NtxyzR4S#omW4PFOPhkV74SXN8VCgbHb1dSv7VML3J49XYwbzj0k">Mega do Aitrepreneur</a>
     </blockquote>
     <blockquote>
     <a href="https://gofile.io/d/Bzdkj3">Go file do Aitrepreneur</a>
     </blockquote></summary></details>
   </blockquote></details>
   
  <details closed><summary>Conta Huggingface</summary>
    <blockquote>
    <a href="https://huggingface.co/">Huggingface.co</a>
    <blockquote>
    <a href="https://huggingface.co/blog/stable_diffusion#license">Licença
  
  <blockquote>
  
  </blockquote></details>
  <details closed><summary>Baixar modelo .ckpt</summary>
    <blockquote>
    <a href="https://huggingface.co/runwayml/stable-diffusion-v1-5">Modelo 1.5</a>
      <blockquote> Para gerar imagens baixar o "v1-5-pruned-emaonly.ckpt"
      </blockquote>
      <blockquote> Para treinamentos baixar o "v1-5-pruned.ckpt"
      </blockquote>
      <img src="/Assets/modelos%2015.PNG" width="400" height="150"/>
      <blockquote>
      <sup>Confirmar o acesso no final da página!</sup>
      </blockquote>
     </blockquote>
      
  <blockquote>
  
  </blockquote></details>
      
  <details closed><summary>Conta Google</summary><blockquote>
    <a href="https://accounts.google.com/signup/">Criar conta Google</a>
    <blockquote>     
  </blockquote></details>
</blockquote></details>
 </div>


---


### [Instalação local](https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo#instala%C3%A7%C3%A3o-local-no-seu-pc) </a> <sup>no seu PC</sup> ou [Usar em qualquer lugar</a> <sup> online em qualquer aparelho</sup>](https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo#usar-em-qualquer-lugar--online-em-qualquer-aparelho)


---
### [Índice de dúvidas e problemas frequentes](https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo#%C3%ADndice-de-d%C3%BAvidas-e-perguntas-frequentes--problema-1-----solu%C3%A7%C3%A3o-1----problema-2-----solu%C3%A7%C3%A3o-2-----)
---
### Instalação local</a> <sup>no seu PC</sup>

![Vídeo publicado em](https://img.shields.io/badge/v%C3%ADdeo%20publicado%20em-26%2F09%2F22-lightgrey) - <a href="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo#instala%C3%A7%C3%A3o-local-no-seu-pc:~:text=Obs%C2%B9%3A%20este%20guia%20sempre%20estar%C3%A1%20mais%20atualizado%20que%20os%20v%C3%ADdeos">Obs¹</a>

<a href="http://www.youtube.com/watch?feature=player_embedded&v=QiwRMlW4qMQ"
target="_blank"><img src="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/blob/main/Assets/thumb%20video%201.png" 
alt="IMAGE ALT TEXT HERE" width="390" height="220" border="10" /></a>

1. Instalação do Python 3.10.6 no Windows
   - Adicionar ao Path e marcar todas as opções
   <img src="/Assets/inst-python.gif" width="400" height="250"/>
2. Instalação do Git
   - Clicar em Next, selecionar todas as opções, e em "choosing the default editor used by Git" selecionar "Use Notepad as Git's editor"
   <img src="/Assets/inst-git2.gif" width="400" height="250"/>
3. Baixar repositóriodo Stable Diffusion
   - Digitar `cmd` na barra de endereço do caminho onde o Stable Diffusion será instalado.
   - Digitar `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git"`
   - Esperar a criação da pasta `\stable diffusion webui`
4. Colocar o Modelo `v1-5-pruned-emaonly.ckpt` no diretório de modelo
   - `Seus-caminhos\Software\stable-diffusion-webui\models\Stable-diffusion`
5. Opcional Colocar o GFPGANv1.4.pth no diretório base, junto do webui.py
6. Rodar o webui-user.bat para instalar o restante dos arquivos
7. Copiar o link gerado e abrir no navegador
    
   <img src="/Assets/link%20para%20interace.PNG" width="400" height="250"/>

---
   
   
### Usar em qualquer lugar </a> <sup>online em qualquer aparelho</sup>

![Vídeo publicado em](https://img.shields.io/badge/v%C3%ADdeo%20publicado%20em-26%2F10%2F22-lightgrey) - <a href="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo#instala%C3%A7%C3%A3o-local-no-seu-pc:~:text=Obs%C2%B9%3A%20este%20guia%20sempre%20estar%C3%A1%20mais%20atualizado%20que%20os%20v%C3%ADdeos">Obs¹</a>

<a href="http://www.youtube.com/watch?feature=player_embedded&v=JQVvl6VZSXg"
target="_blank"><img src="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/blob/main/Assets/sd%20em%20pt%20thumb.png" 
alt="IMAGE ALT TEXT HERE" width="390" height="220" border="10" /></a>



[Passo a passo](https://github.com/M-art-ucci/Fast-Stable-Diffusion-PT-Colab) 


---

<div>
 <h3><details open><summary><b>Índice de dúvidas e problemas frequentes</b></summary>
 <blockquote><details><summary>Tela preta ao tentar gerar imagens - solução 1</summary>
 <blockquote><details><summary>GPU NVIDIA GeForce GTX 1650, 1660 e 1660 Ti</summary>
 <blockquote>Abrir o webui-user.bat com editor de texto e acrescentar o argumento
     
        
     --precision full --no-half
     

  </blockquote></details>
  </blockquote></details>
  
  
  <details><summary>Tela preta ao tentar gerar imagens mesmo após solução 1</summary>
  <blockquote>
  1. Se houver espaços entre os nomes de cada caminho, colocar "-" até onde está o webui-ser.bat
  <blockquote></blockquote>
  2. Abrir o CMD na pasta do webui-seu.bat
  <blockquote></blockquote>
  3. Atualizar para a última versão digitando "git pull"
  <blockquote></blockquote>
  4. Abrir o arquivo webui-user.bat com um editor de texto
  <blockquote></blockquote>
  5. Na frente de "set COMMANDLINE_ARGS=" acrescentar o argumento "--precision full --no-half --medvram --opt-split-attention"  
  <blockquote></blockquote>
  6. Abaixo da linha "set COMMANDLINE_ARGS=" acrescentar o argumento "set OPTIMIZED_TURBO=true"  
  <blockquote></blockquote>
  
  </blockquote></details>
    
  <details><summary>Problema 3</summary><blockquote>
     Solução 3
  
  <blockquote>
  
  </blockquote></details>
      
</blockquote></details>
 </div>
   

---

<a href="https://discord.com/invite/9ZFdQH5YP6">Faça parte da comunidade brasileira de stable diffusion</a>

<a href="https://discord.com/"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Logo" width="180" height="50"><a href="https://discord.com/invite/9ZFdQH5YP6"><img src="https://github.com/M-art-ucci/Stable-Diffusion-pt-BR-Definitivo/blob/main/Assets/logo%20SD%20BR%20nov%2022.png" alt="Logo" width="50" height="50">


</a>
   
 Moderadores
  - M-art-ucci
  - .BieÜ
  - Comunista Trevoso
  - Pedro H.
  - Snow03

---

<h3>Para usar depois</h3>

  Heading com summary
<div>
 <h3><details closed><summary><b>Título do heading</b></summary><blockquote>
  <details><summary>Summary 1</summary><blockquote>
     Lista 1
  </blockquote></details>
  <details><summary>Summary 2</summary><blockquote>
     Lista 2 
  <blockquote>  
  </blockquote></details>
      
</blockquote></details>
 </div>
   
Contorno de tabela

<table>
<tr>
<td>

</td>
</tr>
</table>

Sumários inception

<details closed><summary>nome topo</summary><blockquote>
     <details><summary>nome interno inicial 1</summary><blockquote>
     Nome interno final 1
  </blockquote></details>
     <details closed><summary>nome interno inicial 2</summary><blockquote>
     Nome interno final 2
  </blockquote></details>
  </blockquote></details>

