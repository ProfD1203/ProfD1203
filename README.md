<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head> 
 <script>
 const guid = 'd1f0490029214ace'; 
 </script>
<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">

<head>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
	<style type="text/css">
		html,
		body {
			width: 100%;
			height: 100%;
			margin: 0;
			padding: 0;
			overflow: hidden;
			background-color: rgb(7, 5, 8);
			
		}
		
	</style>
	<style>
		#tabcon {
			background-color: #09000e;
			width: 100%;
		}

		.btn_tab {
			border: .1px solid #161319;
			background: linear-gradient(to right, #070509, #09000e);
			border-radius: 4px;
			color: white;
			width: 100px;
			text-align: start !important;
			backdrop-filter: blur(1px);
			transition: all 0.3s;
		}
		
		.btn_tabusing {
			border: .1px solid #2a232f;
			background: linear-gradient(to right, #170f1c, #09000e);
			border-radius: 4px;
			color: white;
			width: 100px;
			text-align: start !important;
			transition: all 0.3s;
		}

		#container {
			background-color: transparent;
			border: .1px solid #2a232f;
			width:100%;
			height:100%;
			
			transition: all 0.3s;
		}

		.btn_tabadd {
			border: .1px solid #2a232f;
			background: linear-gradient(to right, #170f1c, #09000e);
			border-radius: 4px;
			background-color: black;
			color: white;
			font-size: 13px;
			text-align: center !important;
		}

		.btn_intab {
			border: none;
			background-color: transparent;
			color: white;
			font-family: 'Helvetica Neue', Arial, sans-serif;
			-webkit-font-smoothing: antialiased;
			-moz-osx-font-smoothing: grayscale;
			text-rendering: optimizeLegibility;
  			font-weight: 300;
			font-size: 15px;
			white-space: nowrap;
			overflow: hidden;
			text-overflow: ellipsis;
			transition: all 0.3s;
		}

		::-webkit-scrollbar {
			width: 3px;
			height: 4px;
			background-color: black;
		}

		::-webkit-scrollbar-thumb {
			background-color: transparent;
			max-height: 6px;
			border-radius: 10px;
		}

		.grid-tab {
			display: grid;
			grid-template-columns: auto 30px;
    		gap: 0px;
		}
		.grid-tabcon {
			overflow-x:auto;
			display: grid;
			grid-template-columns: auto 0px;
		}
		.bg-black {
			background-color: black;
		}
		.bg-modal {
			border: .1px solid #2a232f;
			background: linear-gradient(to right, #170f1c, #09000e);
			background-color: rgb(12, 12, 12) !important;
			color: white !important;
		}
		.btnm {
			border: .1px solid #2a232f;
			background: linear-gradient(to right, #170f1c, #09000e);
			background-color: rgb(12, 12, 12);
			color:  white;
			font-family: 'Helvetica Neue', Arial, sans-serif;
			-webkit-font-smoothing: antialiased;
			-moz-osx-font-smoothing: grayscale;
			text-rendering: optimizeLegibility;
  			font-weight: 300;
			font-size: 15px;

		}
		.bg-glass{
            backdrop-filter: blur(1px);
        }

		.form-control-custom {
			display: block;
			width: 100%;
			padding: .375rem .75rem;
			font-size: 1rem;
			font-weight: 400;
			line-height: 1.5;
			color: #212529;
			border: .1px solid #2a232f;
			background: linear-gradient(to right, #170f1c, #09000e);
			background-color: #fff;
			background-clip: padding-box;
			-webkit-appearance: none;
			-moz-appearance: none;
			appearance: none;
			border-radius: .25rem;
			transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out;
		}

		.modal-body-custom {
			border-radius: 4px;
			border: .1px solid #2a232f;
			background: linear-gradient(to right, #170f1c, #09000e);
			position: relative;
			flex: 1 1 auto;
			padding: 1rem;
		}

		.modal-content-custom {
			position: relative;
			display: flex;
			flex-direction: column;
			pointer-events: auto;
			background-color: #fff;

			border: 1px solid rgba(0, 0, 0, .2);
			border-radius: .3rem;
			outline: 0;
			
		}
	</style>
	<meta charset="utf-8" />
	<title></title>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
	<link href="https://kit-pro.fontawesome.com/releases/v6.2.0/css/pro.min.css" rel="stylesheet">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.4/jquery.min.js" integrity="sha512-pumBsjNRGGqkPzKHndZMaAG+bir374sORyzM3uulLV14lN5LyykqNk8eEeUlUkB3U0M4FApyaHraT65ihJhDpQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
	<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/toastify-js/src/toastify.min.css">
</head>
<div class="modal fade bg-glass" id="addtab" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="modal-dialog">
			<div class="modal-content-custom bg-modal">
				
				<div class="modal-body-custom">
					<center>
						<div class="col-lg-10 m-cent ">
							<div class="mb-2 mt-2">
								<div class="mb-2">
									<p class=" mb-1 text-white">Tab Name</p>
									<input type="text" id="tabname" class=".form-control-custom bg-modal" value="">
								</div>
							</div>

							<button type="button" class="btnm w-100 mt-2" onclick="addtab()" data-id="">Add Tab</button>
							
						</div>
					</center>
				</div>
				
			</div>
		</div>
	</div>
<body>
	
	<div class="grid-tabcon bg-black">
		<div id="tabcon" class="d-flex overflow-auto px-2">
			<!-- <div class="grid-tab btn_tab px-1 mx-1"> <button class="text-start btn_intab">test1.lua</button> <button class="btn_intab">X</button> </div> -->
			
			
		</div>
		
		
	</div>
	<script>
		let tab_editing = "";
		let first_tab = "main.lua";


		const tabcon = document.getElementById('tabcon');

		tabcon.addEventListener('wheel', (event) => {
			if (event.deltaY !== 0) {
				tabcon.scrollLeft += event.deltaY;
				event.preventDefault();
			}
		});

        async function start() {
			opentab(first_tab);
			changetabanim(first_tab);

			console.log(first_tab);
			
		}
		async function loadtab(first, addtab) {
			try {
				document.getElementById("tabcon").innerHTML = "";
				const response = await fetch('http://localhost:9911/files', {method: 'GET', headers: {
					'GUID': guid
				}});
				const files = await response.json();
				const tabcon = document.getElementById('tabcon');
				let lastcreate = "main.lua";

				files.forEach(file => {
					if (file.name !== "undefined") {
						
						const tabButton = document.createElement('div');
						tabButton.classList.add('grid-tab', 'btn_tab', 'mb-2', 'px-1', 'mx-1');
						if (first_tab === "") {
							tabButton.innerHTML = `
								<button class="text-start btn_intab" onclick="opentab('${file.name}')" data-file="${file.name}" id="first_tab">${file.name}</button>
								<button class="btn_intab" onclick="deltab('${file.name}')"><i class="fa-solid fa-circle-xmark" style="margin-top: 5px !important;"></i></button>
							`;
							first_tab = file.name;
						} else {
							tabButton.innerHTML = `
								<button class="text-start btn_intab" onclick="opentab('${file.name}')" data-file="${file.name}">${file.name}</button>
								<button class="btn_intab" onclick="deltab('${file.name}')"><i class="fa-solid fa-xmark" style="margin-top: 5px !important;"></i></button>
							`;
						}
						lastcreate = file.name;
						tabcon.appendChild(tabButton);
						
					}
					
				});

				if (addtab) {
					opentab(lastcreate);
				}

				document.getElementById("tabcon").insertAdjacentHTML('beforeend', '<button class="btn_tabadd mb-2" id="open_addtab"><i class="fa-solid fa-plus"></i></button>');

				$("#open_addtab").click(function(){
					const myModal = new bootstrap.Modal('#addtab', {keyboard: false}); 
					myModal.show();
				});

				if (first === true) {
					start();
				}
			} catch (error) {
				console.error('Error fetching files:', error);
			}
		}


		
		async function addtab() {
			try {
				const filename = $("#tabname").val()
				if (filename !== "") {
					const response = await fetch(`http://localhost:9911/addtab/${filename}`, {
						
						method: 'POST',
						headers:{
							'GUID': guid
						}
					});


					if (response.ok) {
						$('#addtab').modal('hide')
						loadtab(false, true);
					} else if (response.status === 409) {
						al(false, `${filename} already exists.`);
					} else {
						al(false, 'Failed to create tab.');
					}
				} else {
					al(false, "Please enter tab name.")
				}
			} catch (error) {
				console.error('Error adding tab:', error);
				al(false, 'Error adding tab: ' + error);
			}
		}

		function changetabanim(activeTab) {
            const tabs = document.querySelectorAll('.grid-tab button[data-file]');
            tabs.forEach(tab => {
                const tabContainer = tab.closest('.grid-tab');
                if (tab.dataset.file === activeTab) {
                    tabContainer.classList.remove('btn_tab');
                    tabContainer.classList.add('btn_tabusing');
                } else {
                    tabContainer.classList.remove('btn_tabusing');
                    tabContainer.classList.add('btn_tab');
                }
            });
        }

        async function opentab(filename) {
			if (filename !== 'undefined') {
				if (tab_editing !== "") {
					await savetab(tab_editing);
				}
				try {
					const response = await fetch(`http://localhost:9911/opentab/${filename}`, {method: 'GET', headers: {
						'GUID': guid
					}});
					const data = await response.text();
						
					monaco.editor.getModels()[0].setValue(data);
					tab_editing = filename;
					changetabanim(filename);
				} catch (error) {
					console.error('Error opening tab:', error);
				}
			}
		}


		async function deltab(filename) {
            if (filename !== "main.lua") {
                try {
                    const response = await fetch(`http://localhost:9911/delete/${filename}`, { headers:{'GUID': guid}, method: 'DELETE' });
                    await loadtab(false);
                    if (tab_editing === filename) {
						tab_editing = ""
                        opentab("main.lua");
                    }
                   
                } catch (error) {
                    console.error('Error deleting file:', error);
                }
            } else {
                al(false, "Cannot delete main.lua!")
            }
		}

		async function savetab(filename) {
			if (filename !== 'undefined') {
				const data = editor.getValue();
				try {
					const response = await fetch(`http://localhost:9911/savetab/${filename}`, {
						method: 'POST',
						
						headers: {
							'GUID': guid, 
							'Content-Type': 'text/plain'
						},
						body: data
					});
					const result = await response.text();
					console.log(`${result} (${filename})`);
				} catch (error) {
					console.error('Error saving file:', error);
				}
			}
		}


        

		

		function al(status, text) {
			if (status === true) { 
				Toastify({
					text: text,
					duration: 2000,
					destination: "https://github.com/apvarun/toastify-js",
					newWindow: true,
					close: true,
					gravity: "top", // `top` or `bottom`
					position: "right", // `left`, `center` or `right`
					stopOnFocus: true, // Prevents dismissing of toast on hover
					style: {
						
						background: "Green",
					},
				onClick: function(){} // Callback after click
				}).showToast();
			} else {
				Toastify({
					text: text,
					duration: 2000,
					destination: "https://github.com/apvarun/toastify-js",
					newWindow: true,
					close: true,
					gravity: "top", // `top` or `bottom`
					position: "right", // `left`, `center` or `right`
					stopOnFocus: true, // Prevents dismissing of toast on hover
					style: {
						
						background: "Red",
					},
				onClick: function(){} // Callback after click
				}).showToast();
			}
		}
		$("#open_addtab").click(function(){
            const myModal = new bootstrap.Modal('#addtab', {keyboard: false}); myModal.show();
        });
		
        loadtab(true);

        window.onbeforeunload = function() {
            savetab(editing_tab);
        };
		
		

  	</script>
	<script>
		let time;
		const waittime = 0;

		function keyPressHandler(event) {
			clearTimeout(time);
			time = setTimeout(function() {
				savetab(tab_editing);
			}, waittime);
		}

		document.addEventListener('keydown', keyPressHandler);
	</script>

	<div id="container"></div>
	
	<script src="vs/loader.js"></script>
	<script type="text/javascript">
		require.config({
			paths: {
				'vs': 'vs'
			}
		});

		var editor;
		var Proposals = [];

		var SetText;
		var ShowMinimap;
		var HideMinimap;
		var EnableAutoComplete;
		var DisableAutoComplete;
		var GetText;
		var AddIntellisense;
		var Refresh;
	


		require(['vs/editor/editor.main'], function () {
			function getDependencyProposals() {
				return Proposals;
			}

			

			monaco.languages.registerCompletionItemProvider('lua', {
				provideCompletionItems: function (model, position) {
					return getDependencyProposals();
				},

			});


			monaco.editor.defineTheme('net-theme-dark', {
				base: 'vs-dark',
				inherit: true,
				colors: {
					"editor.background": '#040007',
				},
				rules: [{
						token: 'global',
						foreground: 'aa80ff', // //FFFFFF
						fontStyle: "bold"
					},
					{
						token: 'keyword',
						foreground: 'cc99cc',
						fontStyle: "bold"
					},
					{
						token: 'comment',
						foreground: '999999'
					},
					{
						token: 'number',
						foreground: 'f99157'
					},
					{
						token: 'string',
						foreground: 'ddccff'
					},
					{
						token: 'Method',
						foreground: 'ffa1dc'
					},
				]
			});

			editor = monaco.editor.create(document.getElementById('container'), {
				language: 'lua',
				theme: "net-theme-dark",
				acceptSuggestionOnEnter: "smart",
				suggestOnTriggerCharacters: true,
				suggestSelection: "recentlyUsed",
				folding: true,
				wordBasedSuggestions : true,
				scrollbar: {
					verticalHasArrows: true,
				},
				dragAndDrop: true,
				links: true,
				minimap: {
					enabled: false,
				},
				showFoldingControls: "always",
				smoothScrolling: true,
			});

			EnableAutoComplete = function(){
				editor.updateOptions({
					suggestOnTriggerCharacters: true,
					acceptSuggestionOnEnter : "smart",
					wordBasedSuggestions : true
				});
			}

			DisableAutoComplete = function(){
				editor.updateOptions({
					suggestOnTriggerCharacters: false,
					acceptSuggestionOnEnter : "off",
					wordBasedSuggestions : false
				});
			}

			window.onresize = function () {
				editor.layout();
			};

			ShowMinimap = function () {
				editor.updateOptions({
					minimap: {
						enabled: true,
					}
				});
			}

			HideMinimap = function () {
				editor.updateOptions({
					minimap: {
						enabled: false,
					}
				});
			}



			editor.onDidChangeModelContent(function (e) {
				window.chrome.webview.postMessage(editor.getValue())
			});

			GetText = function () {
				var value = editor.getValue();
				return value.startsWith('"') && value.endsWith('"') ? value.slice(1, -1) : value;
			}

			SetText = function (x) {
				editor.setValue(x);
			}

			AddIntellisense = function (l, k, d, i) {
				var t;
				switch (k) {
					case "Class":
						t = monaco.languages.CompletionItemKind.Class;
						break;
					case "Color":
						t = monaco.languages.CompletionItemKind.Color;
						break;
					case "Constructor":
						t = monaco.languages.CompletionItemKind.Constructor;
						break;
					case "Enum":
						t = monaco.languages.CompletionItemKind.Enum;
						break;
					case "Field":
						t = monaco.languages.CompletionItemKind.Field;
						break;
					case "File":
						t = monaco.languages.CompletionItemKind.File;
						break;
					case "Folder":
						t = monaco.languages.CompletionItemKind.Folder;
						break;
					case "Function":
						t = monaco.languages.CompletionItemKind.Function;
						break;
					case "Interface":
						t = monaco.languages.CompletionItemKind.Interface;
						break;
					case "Keyword":
						t = monaco.languages.CompletionItemKind.Keyword;
						break;
					case "Method":
						t = monaco.languages.CompletionItemKind.Method;
						break;
					case "Module":
						t = monaco.languages.CompletionItemKind.Module;
						break;
					case "Property":
						t = monaco.languages.CompletionItemKind.Property;
						break;
					case "Reference":
						t = monaco.languages.CompletionItemKind.Reference;
						break;
					case "Snippet":
						t = monaco.languages.CompletionItemKind.Snippet;
						break;
					case "Text":
						t = monaco.languages.CompletionItemKind.Text;
						break;
					case "Unit":
						t = monaco.languages.CompletionItemKind.Unit;
						break;
					case "Value":
						t = monaco.languages.CompletionItemKind.Value;
						break;
					case "Variable":
						t = monaco.languages.CompletionItemKind.Variable;
						break;
				}

				Proposals.push({
					label: l,
					kind: t,
					detail: d,
					insertText: i
				});
			}
			async function load() {
				var docs = await(await fetch('https://solaraweb.vercel.app/asset/docs.txt')).json();

				for (var prop in docs) {
  					  for(var item in docs[prop])
					  {
						    const document = docs[prop][item];
							AddIntellisense(document.label, document.type, document.description, document.insert);
					  }
				}

				for (const Key of ["_G", "_VERSION", "Enum", "game", "plugin", "shared", "script", "workspace", "DebuggerManager", "elapsedTime", "LoadLibrary", "PluginManager", "settings", "tick", "time", "typeof", "UserSettings", "HumanoidRootPart"])
					AddIntellisense(Key, "Keyword", Key, Key);

				for (const Key of ["and", "break", "do", "else", "elseif", "end", "false", "for", "function", "if", "in", "local", "nil", "not", "or", "repeat", "return", "then", "true", "until", "while"])
					AddIntellisense(Key, "Variable", Key, Key);

				for (const Key of ["math.abs", "math.acos", "math.asin", "math.atan", "math.atan2", "math.ceil", "math.cos", "math.cosh", "math.deg", "math.exp", "math.floor", "math.fmod", "math.frexp", "math.huge", "math.ldexp", "math.log", "math.max", "math.min", "math.modf", "math.pi", "math.pow", "math.rad", "math.random", "math.randomseed", "math.sin", "math.sinh", "math.sqrt", "math.tan", "math.tanh", "table.concat", "table.foreach", "table.foreachi", "table.sort", "table.insert", "table.remove", "Color3.new", "Instance.new", "BrickColor.new", "Vector3.new", "Vector2.new", "debug.getinfo", "string.byte", "string.char", "string.dump", "string.find", "string.format", "string.gmatch", "string.gsub", "string.len", "string.lower", "string.match", "string.rep", "string.reverse", "string.sub", "string.upper", "coroutine.create", "coroutine.resume", "coroutine.running", "coroutine.status", "coroutine.wrap", "coroutine.yield"])
					AddIntellisense(Key, "Method", Key, Key);

				for (const Key of ["Drawing", "debug", "Instance", "Color3", "Vector3", "Vector2", "BrickColor", "math", "table", "string", "coroutine", "Humanoid", "ClickDetector", "LocalScript", "Model", "ModuleScript", "Mouse", "Part", "Script", "Tool", "RunService", "UserInputService", "Workspace", "ReplicatedFirst", "SoundService", "Character", "CoreGui", "ReplicatedStorage", "Lighting", "Players", "PlayerGui", "PlayerScript", "LocalPlayer", "Parent"])
					AddIntellisense(Key, "Class", Key, Key);

				for (const Key of ["print", "warn", "wait", "info", "printidentity", "assert", "collectgarbage", "error", "getfenv", "getmetatable", "setmetatable", "ipairs", "loadfile", "loadstring", "newproxy", "next", "pairs", "pcall", "spawn", "rawequal","rawget", "rawset", "select", "tonumber", "tostring", "type", "unpack", "xpcall", "delay", "stats", ":Remove()", ":BreakJoints()", ":GetChildren()", ":FindFirstChild()", ":FireServer()", ":InvokeServer()", ":ClearAllChildren()", ":Clone()", ":Destroy()", ":FindFirstAncestor()", ":FindFirstAncestorOfClass()", ":FindFirstAncestorWhichIsA()", ":FindFirstChildOfClass()", ":FindFirstChildWhichIsA()", ":GetDebugId()", ":GetDescendants()", ":GetFullName()", ":IsA()", ":GetPropertyChangedSignal()", ":IsAncestorOf()", ":IsDescendantOf()", ":WaitForChild()", ":Connect()", ":AncestryChanged()", ":Changed()", ":ChildAdded()", ":ChildRemoved()", ":DescendantAdded()", ":DescendantRemoving()", ":GetService()", ":GetObjects()", ":HttpGet()", ":Wait()"])
					AddIntellisense(Key, "Function", Key, Key.includes(":") ? Key.substring(1, Key.length) : Key);


                for (const Key of ["Visible", "Color", "Transparency", "Thickness", "From", "To", "Text", "Size", "Center", "Outline", "OutlineColor", "Position", "TextBounds", "Font", "Data", "Rounding", "NumSides", "Radius", "Filled", "PointA", "PointB", "PointC", "PointD"])
					AddIntellisense(Key, "Property", "Property for Drawing Library", Key);

			}
			load();
			Refresh = function () {
				var text = GetText();
				SetText('');
				editor.trigger('keyboard', 'type', {
					text: text
				});
			}
			
			window.editorInstance = editor;

			// Modify this method
			editor.getEditorValue = function() {
				var value = editor.getValue();
				return JSON.stringify({ value: value });
			};
		});
	</script>
</body>

</html>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/toastify-js"></script>

<script>
	
</script>