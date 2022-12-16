<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>App de sorteos Grupo Automotriz</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
	<link rel="stylesheet" type="text/css" href="css/estilos.css">
</head>
<body>
	<div class="container-fluid" id="app">
		<div class="row align-items-center nav">
			<div class="col position-relative">
				<img src="img/gorro.png" class="position-absolute" width="100" style="top:-40px; left:0;	">
				<img src="img/logo.png" width="250">
			</div>
			<div class="col-auto">
				<!--<div class="etiqueta-participantes">Participantes <span>{{cantParticipantes()}}</span></div>-->
			</div>
		</div>
		<header class="row position-relative">
			<div class="col">
				<div class="row">
					<div class="col">
						<h1>Desea que en esta <span class="rs">Navidad</span> se encienda la Luz de la <span class="rs">Esperanza</span></h1>
						<h2>y Prosperidad en nuestras <span class="rs">familias.</span></h2>
					</div>
				</div>
				<div class="cajaForm position-absolute ">
					<div>
							<div class="input-group">
							  <div class="input-group-prepend">
							    <span class="input-group-text" id="basic-addon1">
							    	<svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="green" class="bi bi-gift" viewBox="0 0 16 16">
									  <path d="M3 2.5a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0v.006c0 .07 0 .27-.038.494H15a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1v7.5a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 1 14.5V7a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h2.038A2.968 2.968 0 0 1 3 2.506V2.5zm1.068.5H7v-.5a1.5 1.5 0 1 0-3 0c0 .085.002.274.045.43a.522.522 0 0 0 .023.07zM9 3h2.932a.56.56 0 0 0 .023-.07c.043-.156.045-.345.045-.43a1.5 1.5 0 0 0-3 0V3zM1 4v2h6V4H1zm8 0v2h6V4H9zm5 3H9v8h4.5a.5.5 0 0 0 .5-.5V7zm-7 8V7H2v7.5a.5.5 0 0 0 .5.5H7z"/>
									</svg>
							    </span>
							  </div>
							  <input type="text" class="form-control" readonly placeholder="¿Quién podrá ser?" v-model="ganador">
							  <div>
							  		<button class="btn" v-on:click="generar(cont)" :disabled="estatus">Descubrir</button>
							  </div>
							</div>
							<small>Éxitos y bendiciones</small>
					</div>
				</div>
				
			</div>
		</header>
		<div class="row mb-2 cajaSeparador">
			<div class="col">
				
			</div>
		</div>
		<div class="row  mb-2">
			<div class="col bg-gris mr-2">
				<table class="table">
				  <thead class="thead-light">
				    <tr>
				      <th scope="col">#</th>
				      <th scope="col">Lista de ganadores</th>				 
				    </tr>
				  </thead>
				  <tbody>
				    <tr v-if="lstGanadores.length == 0">
				     		<th scope="row">#</th>
				      		<td>No hay ganadores aún</td>	
				    </tr>
				    <tr v-else v-for="(ganador,index) in lstGanadores">
				     	<th scope="row">{{index+1}}</th>
				      	<td>{{ganador.nombre}} {{ganador.apellido}}</td>
				      	<td>
				      		<button v-on:click="eliminarGanador(index)" class="btn btn-danger p-1">
				      			<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="white" class="bi bi-x-square" viewBox="0 0 16 16">
								  <path d="M14 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h12zM2 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2H2z"/>
								  <path d="M4.646 4.646a.5.5 0 0 1 .708 0L8 7.293l2.646-2.647a.5.5 0 0 1 .708.708L8.707 8l2.647 2.646a.5.5 0 0 1-.708.708L8 8.707l-2.646 2.647a.5.5 0 0 1-.708-.708L7.293 8 4.646 5.354a.5.5 0 0 1 0-.708z"/>
								</svg>
				      		</button>
				      	</td>
				    </tr>						    	

				  </tbody>
				</table>
			</div>
			<div id="cjContador" class="col p-3  text-center d-flex align-items-center flex-column">
				<div>
					<h1>GANADOR</h1>
				</div>
				<div class="cj-contador">
					<div class="contador-header">
						{{cronometro}}
					</div>
					<div class="contador-footer">
						SEGUNDOS
					</div>
				</div>
			</div>
			<div class="col bg-gris ml-2 p-0">
				<table class="table">
				  <thead class="thead-light">
				    <tr>
				      <th scope="col">#</th>
				      <th scope="col">Regalos para los ganadores</th>				 
				    </tr>
				  </thead>
				  <tbody>
				    <tr v-for="(premio,index) in lstPremios">
				      <th scope="row">{{index+1}}</th>
				      <td>{{premio.nombre}}</td>				     
				    </tr>			
				  </tbody>
				</table>
			</div>
		</div>
		<footer class="row ">
			<div class="col text-center lead">
				DESARROLLADO POR EL DEPARTAMENTO DE PROGRAMACIÓN Y TECNOLOGÍA
			</div>
		</footer>
	</div>
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
<script type="text/javascript">
	var app= new Vue({
		el:'#app',
		data:{
			cont:3,
			intervalo:0,
			estatus:false,
			lstParticipantes:[
				{nombre:'María Eugenia',apellido:'Da Silva'},
				{nombre:'Carlos Eduardo',apellido:'Agrela'},
				{nombre:'Evaristo José',apellido:'Angulo'},
				{nombre:'Yegnic Lucmila',apellido:'Angulo'},
				{nombre:'Grisely',apellido:'Aricaguan'},
				{nombre:'Leopoldo',apellido:'Pinedo'},
				{nombre:'Raiza',apellido:'Blanco'},
				{nombre:'Luis Enrique',apellido:'Blanco'},
				{nombre:'Yorjans Jesus',apellido:'Blandin'},
				{nombre:'Angrid Maoli',apellido:'Bolemos'},
				{nombre:'Alexandra',apellido:'Carrasquel'},
				{nombre:'America Josefina',apellido:'Carrasquel'},
				{nombre:'Nicolas',apellido:'Carreño'},
				{nombre:'Armando',apellido:'Ceballo'},
				{nombre:'Omarilys',apellido:'Cedeño'},
				{nombre:'Johanna',apellido:'Celis'},
				{nombre:'Yoncir',apellido:'Chiquito'},
				{nombre:'Nelly',apellido:'Codallo'},
				{nombre:'Francis',apellido:'Colmenares'},
				{nombre:'Virginia',apellido:'Crespo'},
				{nombre:'Doward',apellido:'Crosby'},
				{nombre:'Jacqueline',apellido:'Cuenta'},
				{nombre:'Carla',apellido:'Da Costa'},
				{nombre:'Arsenio',apellido:'Diaz'},
				{nombre:'Kleber',apellido:'Diaz'},
				{nombre:'Echezuria',apellido:'Daymmar'},
				{nombre:'Evans',apellido:'Luis'},
				{nombre:'Elvis',apellido:'Figueroa'},
				{nombre:'Victor',apellido:'Fonseca'},
				{nombre:'Andres',apellido:'FRANCO'},
				{nombre:'Belkisael',apellido:'Delgado'},
				{nombre:'Juan',apellido:'Gedler'},
				{nombre:'Juana',apellido:'Solobella'},
				{nombre:'Argenis',apellido:'Gonzalez'},
				{nombre:'Yenny',apellido:'Hernandez'},
				{nombre:'Oliver',apellido:'Hurtado'},
				{nombre:'Douglas',apellido:'Jimenez'},
				{nombre:'Marja',apellido:'Julio'},
				{nombre:'Nhayret',apellido:'Lopez'},
				{nombre:'Antonio',apellido:'Martniez'},
				{nombre:'Veruska',apellido:'Martinez'},
				{nombre:'Leandro',apellido:'Medina'},
				{nombre:'Briggitte',apellido:'Mesa'},
				{nombre:'Yeferson',apellido:'Milano'},
				{nombre:'Alfredo',apellido:'Moreno'},
				{nombre:'Erick',apellido:'Muñoz'},
				{nombre:'Wilfredo',apellido:'Nuñez'},
				{nombre:'Martha',apellido:'Ocampo'},
				{nombre:'Maria Soledad',apellido:'Oliveros'},
				{nombre:'Juan Daniel',apellido:'Olivo'},
				{nombre:'Ynmaculada',apellido:'Orellana'},
				{nombre:'Daniela',apellido:'Ortega'},
				{nombre:'Manuel',apellido:'Ospino'},
				{nombre:'Eustaquio',apellido:'Pagano'},
				{nombre:'Lilibeth',apellido:'Peña'},
				{nombre:'Eliecer',apellido:'Perez'},
				{nombre:'Luis Eduardo',apellido:'Perez'},
				{nombre:'Asdrubal',apellido:'Perez'},
				{nombre:'Jesus Alfredo',apellido:'Perez'},
				{nombre:'Ronni',apellido:'Piamo'},
				{nombre:'Aldimar',apellido:'Pimentel'},
				{nombre:'Damelis',apellido:'Piña'},
				{nombre:'Carlos',apellido:'Quintana'},
				{nombre:'Daniel Alexander',apellido:'Rangel'},
				{nombre:'Henger',apellido:'Reyes'},
				{nombre:'José Gregorio',apellido:'Rivas'},
				{nombre:'Francisco Javier',apellido:'Robles'},
				{nombre:'Francy',apellido:'Rodriguez'},
				{nombre:'Shedymar',apellido:'Rodriguez'},
				{nombre:'Carmen',apellido:'Rosales'},
				{nombre:'Carmen ',apellido:'Salinas'},
				{nombre:'Enrique',apellido:'Sanchez'},
				{nombre:'Henry',apellido:'Silva'},
				{nombre:'Alirio',apellido:'Suarez'},
				{nombre:'Sergio',apellido:'Torres'},
				{nombre:'Ruvicney',apellido:'Ulloa'},
				{nombre:'Wilmere',apellido:'Vargas'},
				{nombre:'Francisco',apellido:'Vasquez'},
				{nombre:'Maribel',apellido:'Vasqiez'},
				{nombre:'Leonardo',apellido:'Verdu'},
				{nombre:'Francisco Javier',apellido:'Villar'},
				{nombre:'Jose Rafael',apellido:'Yacuas'},
				{nombre:'Carlos',apellido:'Yanez'},
				{nombre:'Yovanna',apellido:'Zapata'}
			],
			lstPremios:[
				{nombre:'SAMSUNG SMART TV FULL HD 40'},
				{nombre:'AIWA SMART TV ANDROID TV 32'},
				{nombre:'CELULAR SAMSUNG A13 4GB RAM 64GB ROM'},
				{nombre:'CELULAR SAMSUNG A03S 3GB RAM 32 GB ROM'},
				{nombre:'CELULAR SAMSUNG A03S 3GB RAM 32 GB ROM'}
			],
			ganador:'',
			lstGanadores:[
			]
		},
		methods:{
			cantParticipantes:function(){
				let cant=this.lstParticipantes.length;
				return cant;
			},
			getNumeroAleatoreo:function(max){
				return Math.floor(Math.random() * max);
			},
			generar:function(cont){
				if(cont !=0){
					this.estatus=!this.estatus;
				}else{
					let cantParticipantes=this.cantParticipantes(),
					numAleatoreo=this.getNumeroAleatoreo(cantParticipantes),
					{nombre,apellido}=this.lstParticipantes[numAleatoreo];
					this.ganador=nombre +' '+apellido;
					this.lstGanadores.push({
						nombre,
						apellido,
					});

					
				}
			},
			empezarTiempo:function(){
				clearInterval(this.intervalo);
				if(this.cont >0){
		         this.intervalo = setInterval(()=>{
		           	 			this.cont = this.cont - 1
		        			},1000)
				}else{
					clearInterval(this.ivl);
					this.cont=3;
					this.estatus=!this.estatus;
				}

			},
			eliminarGanador(index){
				let id=index;
				if(confirm('¿Segura que deseas eliminar este ganador?')){
					this.lstGanadores.splice(id,1);

				}
			}
		},
		computed:{
			cronometro:function(){
				let cont=this.cont;
				if(this.estatus==true){
					this.empezarTiempo();
				}
				if(cont ==0){
					this.generar(cont);
					document.querySelector('#cjContador').className+=" bg-confeti";
				}
				return cont;
			}
		}
	})
</script>
</body>
</html>