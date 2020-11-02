# Graficacion-practica2b
#uso de lineas en pantalla completa 
#codigo 
parte donde se utiliza posisiciones para realizar el codigo 
public class GraphicListener implements GLEventListener{
 public void display(GLAutoDrawable arg0) {
	 
 // tamano de las lineas
 gl.glLineWidth(2);
 // crear lineas
 gl.glBegin(GL.GL_LINES);
 
 //*******************************************************************HORIZONTAL*******************************************************************
  // X positivo color  horizontal
 gl.glColor3f(0,1,1);         
 
 //linea 1
 gl.glVertex2d(-900,900); // estas funciones son para pocionar las lineas 
gl.glVertex2d(800,900);

 //linea 2
 gl.glVertex2d(-800,800);
 gl.glVertex2d(700,800);

 //linea 3
gl.glVertex2d(-700,700);
gl.glVertex2d(600,700);

//linea 4
gl.glVertex2d(-600,600);
gl.glVertex2d(500,600);

//linea 5
gl.glVertex2d(-500,500);
 gl.glVertex2d(400,500);

//linea 6
gl.glVertex2d(-400,400);
gl.glVertex2d(300,400);

//linea 7
gl.glVertex2d(-300,300);
 gl.glVertex2d(200,300);
 
//linea 8
gl.glVertex2d(-200,200);
gl.glVertex2d(100,200);

//linea 9
gl.glVertex2d(-150,100);
 gl.glVertex2d(50,100);

 
 //************************************************************************************VERTICAL****************************************************
gl.glColor3f(0,1,1);// misma duncion de color de las lineas 

 //linea  1
 gl.glVertex2d(-900,-900);
 gl.glVertex2d(-900,900);
 
//Linea vertical 2
 gl.glVertex2d(-800,-800);
 gl.glVertex2d(-800,800);

 //linea 3
 gl.glVertex2d(-700,-700);
 gl.glVertex2d(-700,700);

 //linea 4
 gl.glVertex2d(-600,-600);
 gl.glVertex2d(-600,600);
 
 //linea 5
 gl.glVertex2d(-500,-500);
 gl.glVertex2d(-500,500);
 
//linea 6
 gl.glVertex2d(-400,-400);
 gl.glVertex2d(-400,400);

//linea 7
 gl.glVertex2d(-300,-300);
 gl.glVertex2d(-300,300);
 
//linea 8
 gl.glVertex2d(-200,-200);
 gl.glVertex2d(-200,200);
 
//linea 9
 gl.glVertex2d(-150,-100);
 gl.glVertex2d(-150,100);


 
 
 //*********************************************************************************HORIZONTAL*******************************************************************************
 //lineas horizontal 
 gl.glColor3f(0,1,1);// el clolor de la lineahorizontal de la posiciones en la coordenada x negativo
 //posiciones para la lineas aqui va en desenso 
gl.glVertex2d(800,-900);
gl.glVertex2d(-900,-900);

//linea 8
gl.glVertex2d(700,-800);
gl.glVertex2d(-800,-800);

//linea 7
gl.glVertex2d(600,-700);
gl.glVertex2d(-700,-700);

 //linea 6
 gl.glVertex2d(500,-600);
gl.glVertex2d(-600,-600);

//linea 5
gl.glVertex2d(400,-500);
gl.glVertex2d(-500,-500);

//linea 4
 gl.glVertex2d(300,-400);
 gl.glVertex2d(-400,-400);

 //linea 3
 gl.glVertex2d(200,-300);
gl.glVertex2d(-300,-300);

//linea 2
gl.glVertex2d(100,-200);
gl.glVertex2d(-200,-200);

//linea 1
gl.glVertex2d(50,-100);
 gl.glVertex2d(-150,-100);


//********************************************************************************************VERTICAL******************************************************************
 //lineas vertical 
 gl.glColor3f(0,1,1);// el clolor de la linea verticalde la posiciones en la coordenada y positivo
 // posiciones para la lineas
 
 //;inea 1
 gl.glVertex2d(800,-900);
 gl.glVertex2d(800,900);
 
//linea 2
gl.glVertex2d(700,-800);
gl.glVertex2d(700,800);

 //linea 3
gl.glVertex2d(600,-700);
gl.glVertex2d(600,700);

 //linea 4
gl.glVertex2d(500,-600);
gl.glVertex2d(500,600);

//linea 5
gl.glVertex2d(400,-500);
gl.glVertex2d(400,500);

//linea 6
gl.glVertex2d(300,-400);
 gl.glVertex2d(300,400);

//linea 7
gl.glVertex2d(200,-300);
gl.glVertex2d(200,300);

//linea 8
gl.glVertex2d(100,-200);
 gl.glVertex2d(100,200);

//linea 9
gl.glVertex2d(50,-100);
gl.glVertex2d(50,100);

 //Deshabilitamos la creacion de lineas (de la maquina de estados )
 gl.glEnd();
 gl.glFlush();
 }
 

#Ejecucion
![Captura de pantalla (25)](https://user-images.githubusercontent.com/73785441/97922267-cd466100-1d21-11eb-80db-c73d28e4e4ae.png)
