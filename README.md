<h1>xbim/viewer - Mini Tutorial</h1>

<h1>[EN]</h1>

<h2>First Steps</h2>

-   To create a 3D viewer, the repository in <a href="https://github.com/xBimTeam" target="_blank">xBimTeam</a>
-   You will need an IFC (Industry Foundation Classes) file [Common file among software that use the BIM (Building Information Modeling) Methodology]

<h3>PS: It is necessary basic knowledge in <b>npm, JavaScript, TypeScript e C#</b><h3>

<br>
<hr>

<h2>Creating a 3D web viewer</h2>

<br>

<h3>1. Clone the repository <a href="https://github.com/xBimTeam/XbimWebUI" target="_blank">XBimWebUI</a></h3>

<br>

<h3>2. In the repository, install the package:</h3>

```
npm install @xbim/viewer
```

<br>

<h3>3. Then, run the command:</h3>

```
npm run start
```

<br>

PS: The examples shown are in development mode, and still need to be compiled and sent to production mode.

<br>

<h3>4. In the <b>examples</b> folder, in one of the three files, you can add functionality present in the documentation <a href="https://docs.xbim.net/XbimWebUI/" target="_blank">@xbim/viewer</a><h4>

<br>

<b>Tip: It will be very common to do <i>import</i> or <i>export</i> between files</b>

<br>

<h3>5. Added the desired features, send them to production with the command:</h3>

```
npm run build:dev
```

PS: With that the files in TypeScript will be compiled to JavaScript, allowing visualization in the browser.

<br>

<hr>

<h2>Converting an IFC file to .wexbim</h2>

<br>

<h3><b>PS: For this step, use: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></h3>

<br>

<h3>1. Clone the repository <a href="https://github.com/xBimTeam/XbimSamples" target="_blank">XBimSamples</a></h3>
<br>

<h3>2. Open the file <b>XbimSamples.sln</b></h3>
<br>

<h3>3. Set <b>CreateWexBIM</b> as a startup project</h3>
<br>

<h3>4. Build this solution</h3>
<br>

<h3>5. Choose the file to be converted</h3>
<br>

<h3>6. The converted file will be in the same location</h3>
<br>

<hr>

<h2>Converting an IFC file to JSON</h2>

<br>

<h3><b>PS: For this step, use: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></h3>

<h3><b>PS: This JSON translator might not bring all the information from the IFC file</h3>

<br>

<h3>1. Clone the repository <a href="https://github.com/xBimTeam/XbimExchange" target="_blank">XbimExchange</a></h3>
<br>

<h3>2. Open the file <b>XbimSamples.sln</b></h3>
<br>

<h3>3. Define <b>Xbim.COBieLiteUK.Client</b> as a startup project</h3>
<br>

<h3>4. Build this solution</h3>
<br>

<h3>5. Enable the option <b>Use ExId as EntityId</b></h3>
<br>

<h3>6. Click on the option <b>Set Filter Defaults</b></h3>
<br>

<h3>7. Enable all options in <b>Component Sheet, TypeSheet e Assembly Sheet</b></h3>
<br>

<h3>8. Change the <b>XLSX</b> file format to <b>JSON</b></h3>
<br>

<h3>9. Select the file to be converted</h3>
<br>

<h3>10. Click on <b>Generate</b></h3>
<br>

<h1>[PT-BR]</h1>

<h2>Primeiros Passos</h2>

-   Para criar um visualizador 3D, verifique o respositório em <a href="https://github.com/xBimTeam" target="_blank">xBimTeam</a>
-   Será preciso um arquivo IFC (Industry Foundation Classes) [Arquivo comum entre softwares que utilizam a Metodologia BIM (Building Information Modeling)]

<h3>Obs.: É preciso conhecimentos prévios básicos em <b>npm, JavaScript, TypeScript e C#</b><h3>

<br>
<hr>

<h2>Criando um visualizador 3D para web</h2>

<br>

<h3>1. Clone o repositório <a href="https://github.com/xBimTeam/XbimWebUI" target="_blank">XBimWebUI</a></h3>

<br>

<h3>2. No respositório, instale o pacote:</h3>

```
npm install @xbim/viewer
```

<br>

<h3>3. Em seguida, execute o comando:</h3>

```
npm run start
```

<br>

Obs.: Os exemplos mostrados, estão no modo de desenvolvimento, e ainda precisam ser compilados e mandados para o modo de produção

<br>

<h3>4. Na pasta <b>examples</b>, em um dos três arquivos, pode-se adicionar funcionalidades presentes na documentação <a href="https://docs.xbim.net/XbimWebUI/" target="_blank">@xbim/viewer</a><h4>

<br>

<b>Dica: Será muito comum fazer <i>import</i> ou <i>export</i> entre os arquivos</b>

<br>

<h3>5. Adicionado as funcionalidades desejadas, mande-os para produção com o comando:</h3>

```
npm run build:dev
```

Obs.: Com isso os arquivos em TypeScript serão compilados para JavaScript, permitindo a visualização no navegador.

<br>

<hr>

<h2>Convertendo um arquivo IFC em .wexbim</h2>

<br>

<h3><b>Obs.: Para esta etapa, use o: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></h3>

<br>

<h3>1. Clone o repositório <a href="https://github.com/xBimTeam/XbimSamples" target="_blank">XBimSamples</a></h3>
<br>

<h3>2. Abra o arquivo <b>XbimSamples.sln</b></h3>
<br>

<h3>3. Defina <b>CreateWexBIM</b> como um projeto de inicialização</h3>
<br>

<h3>4. Compile essa solução</h3>
<br>

<h3>5. Escolha o arquivo que será convertido</h3>
<br>

<h3>6. O arquivo convertido estará no mesmo local</h3>
<br>

<hr>

<h2>Convertendo um arquivo IFC em JSON</h2>

<br>

<h3><b>Obs1.: Para esta etapa, use o: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></h3>

<h3><b>Obs2.: Esse conversor JSON pode não trazer todas as informações do arquivo IFC</h3>

<br>

<h3>1. Clone o repositório <a href="https://github.com/xBimTeam/XbimExchange" target="_blank">XbimExchange</a></h3>
<br>

<h3>2. Abra o arquivo <b>XbimSamples.sln</b></h3>
<br>

<h3>3. Defina <b>Xbim.COBieLiteUK.Client</b> como um projeto de inicialização</h3>
<br>

<h3>4. Compile essa solução</h3>
<br>

<h3>5. Habilite a opção <b>Use ExId as EntityId</b></h3>
<br>

<h3>6. Clique na opção <b>Set Filter Defaults</b></h3>
<br>

<h3>7. Habilite todas as opções em <b>Component Sheet, TypeSheet e Assembly Sheet</b></h3>
<br>

<h3>8. Mude o formato do arquivo <b>XLSX</b> para <b>JSON</b></h3>
<br>

<h3>9. Selecione o arquivo que será convertido</h3>
<br>

<h3>10. Clique em <b>Generate</b></h3>

<h2>Créditos</h2>

<h3>Feito por @lukaofirst e @JoaoVictorCf1401</h3>
