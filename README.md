<h1>xbim/viewer - Mini Tutorial</h1>

<h1>[EN]</h1>

<h2>First Steps</h2>

-   To create a 3D viewer, the repository in <a href="https://github.com/xBimTeam" target="_blank">xBimTeam</a>
-   You will need an IFC (Industry Foundation Classes) file [Common file among software that use the BIM (Building Information Modeling) Methodology]

<p>PS: It is necessary basic knowledge in <b>npm, JavaScript, TypeScript and C#</b><p>
<br>

<h2>Creating a 3D web viewer</h2>

<br>

<p>1. Clone the repository <a href="https://github.com/xBimTeam/XbimWebUI" target="_blank">XBimWebUI</a></p>

<br>

<p>2. In the repository, install the package:</p>

```
npm install @xbim/viewer
```

<br>

<p>3. Then, run the command:</p>

```
npm run start
```

<br>

PS: The examples shown are in development mode, and still need to be compiled and sent to production mode.

<br>

<p>4. In the <b>examples</b> folder, in one of the three files, you can add functionality present in the documentation <a href="https://docs.xbim.net/XbimWebUI/" target="_blank">@xbim/viewer</a><p>

<br>

<b>Tip: It will be very common to do <i>import</i> or <i>export</i> between files</b>

<br>

<p>5. Added the desired features, send them to production with the command:</p>

```
npm run build:dev
```

PS: With that the files in TypeScript will be compiled to JavaScript, allowing visualization in the browser.

<br>
<h2>Converting an IFC file to .wexbim</h2>

<br>

<p><b>PS: For this step, use: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></p>

<br>

<p>1. Clone the repository <a href="https://github.com/xBimTeam/XbimSamples" target="_blank">XBimSamples</a></p>
<br>

<p>2. Open the file <b>XbimSamples.sln</b></p>
<br>

<p>3. Set <b>CreateWexBIM</b> as a startup project</p>
<br>

<p>4. Build this solution</p>
<br>

<p>5. Choose the file to be converted</p>
<br>

<p>6. The converted file will be in the same location</p>
<br>

<h2>Converting an IFC file to JSON</h2>

<br>

<p><b>PS: For this step, use: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></p>

<p><b>PS: This JSON translator might not bring all the information from the IFC file</b></p>

<br>

<p>1. Clone the repository <a href="https://github.com/xBimTeam/XbimExchange" target="_blank">XbimExchange</a></p>
<br>

<p>2. Open the file <b>XbimSamples.sln</b></p>
<br>

<p>3. Define <b>Xbim.COBieLiteUK.Client</b> as a startup project</p>
<br>

<p>4. Build this solution</p>
<br>

<p>5. Enable the option <b>Use ExId as EntityId</b></p>
<br>

<p>6. Click on the option <b>Set Filter Defaults</b></p>
<br>

<p>7. Enable all options in <b>Component Sheet, TypeSheet e Assembly Sheet</b></p>
<br>

<p>8. Change the <b>XLSX</b> file format to <b>JSON</b></p>
<br>

<p>9. Select the file to be converted</p>
<br>

<p>10. Click on <b>Generate</b></p>

<h2>Credits</h2>

<p>Made by <a href="https://github.com/lukaofirst" target="_blank">@lukaofirst</a> and <a href="https://github.com/JoaoVictorCf1401" target="_blank">@JoaoVictorCf1401</a></p>

<br>
<br>
<br>

<h1>[PT-BR]</h1>

<h2>Primeiros Passos</h2>

-   Para criar um visualizador 3D, verifique o respositório em <a href="https://github.com/xBimTeam" target="_blank">xBimTeam</a>
-   Será preciso um arquivo IFC (Industry Foundation Classes) [Arquivo comum entre softwares que utilizam a Metodologia BIM (Building Information Modeling)]

<p>Obs.: É preciso conhecimentos prévios básicos em <b>npm, JavaScript, TypeScript e C#</b><p>
<br>

<h2>Criando um visualizador 3D para web</h2>
<br>

<p>1. Clone o repositório <a href="https://github.com/xBimTeam/XbimWebUI" target="_blank">XBimWebUI</a></p>
<br>

<p>2. No respositório, instale o pacote:</p>

```
npm install @xbim/viewer
```

<br>

<p>3. Em seguida, execute o comando:</p>

```
npm run start
```

<br>

Obs.: Os exemplos mostrados, estão no modo de desenvolvimento, e ainda precisam ser compilados e mandados para o modo de produção

<br>

<p>4. Na pasta <b>examples</b>, em um dos três arquivos, pode-se adicionar funcionalidades presentes na documentação <a href="https://docs.xbim.net/XbimWebUI/" target="_blank">@xbim/viewer</a><p>

<br>

<b>Dica: Será muito comum fazer <i>import</i> ou <i>export</i> entre os arquivos</b>

<br>

<p>5. Adicionado as funcionalidades desejadas, mande-os para produção com o comando:</p>

```
npm run build:dev
```

Obs.: Com isso os arquivos em TypeScript serão compilados para JavaScript, permitindo a visualização no navegador.

<br>

<h2>Convertendo um arquivo IFC em .wexbim</h2>

<br>

<p><b>Obs.: Para esta etapa, use o: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></p>

<br>

<p>1. Clone o repositório <a href="https://github.com/xBimTeam/XbimSamples" target="_blank">XBimSamples</a></p>
<br>

<p>2. Abra o arquivo <b>XbimSamples.sln</b></p>
<br>

<p>3. Defina <b>CreateWexBIM</b> como um projeto de inicialização</p>
<br>

<p>4. Compile essa solução</p>
<br>

<p>5. Escolha o arquivo que será convertido</p>
<br>

<p>6. O arquivo convertido estará no mesmo local</p>
<br>

<h2>Convertendo um arquivo IFC em JSON</h2>

<br>

<p><b>Obs1.: Para esta etapa, use o: <a href="https://visualstudio.microsoft.com/pt-br/downloads/" target="_blank">Visual Studio 2019 Community</a></b></p>

<p><b>Obs2.: Esse conversor JSON pode não trazer todas as informações do arquivo IFC</b></p>

<br>

<p>1. Clone o repositório <a href="https://github.com/xBimTeam/XbimExchange" target="_blank">XbimExchange</a></p>
<br>

<p>2. Abra o arquivo <b>XbimSamples.sln</b></p>
<br>

<p>3. Defina <b>Xbim.COBieLiteUK.Client</b> como um projeto de inicialização</p>
<br>

<p>4. Compile essa solução</p>
<br>

<p>5. Habilite a opção <b>Use ExId as EntityId</b></p>
<br>

<p>6. Clique na opção <b>Set Filter Defaults</b></p>
<br>

<p>7. Habilite todas as opções em <b>Component Sheet, TypeSheet e Assembly Sheet</b></p>
<br>

<p>8. Mude o formato do arquivo <b>XLSX</b> para <b>JSON</b></p>
<br>

<p>9. Selecione o arquivo que será convertido</p>
<br>

<p>10. Clique em <b>Generate</b></p>
<br>

<h2>Créditos</h2>

<p>Feito por <a href="https://github.com/lukaofirst" target="_blank">@lukaofirst</a> e <a href="https://github.com/JoaoVictorCf1401" target="_blank">@JoaoVictorCf1401</a></p>