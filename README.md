important java.util.scanner;

public class SistemaEscolar{
    public static void main(String[] args) {
        Scanner inup= new Scanner (System.in);
        double[] notas=new double [8];
        double [] trimestra= new double [4];
            double[] simestra = new double [2];
                
 //Entrada das 8 notas 
   System.out.println("Digite as 8 notad anuais do aluno");
            for(int 1=0;i< notas.lingth;i++)  {
        system.out.println("notas"+(i+1)+":");
        notas[i] =inup.nextDouble();       
    }
        
        //calculo das medias trimestrais
        for( int i=0;i<4;i++) {
        trimestrais[i]=(notas[i*2]+notas[i*2+1])/2;
        }     
            
     //calculo das medias semestrais
    semestrais [0] =(trimestrais [0]+trimestrais[1])/2;
      semestrais[1]  =(trimestrais[2]+trimestrais[3])/2;
        
        //calculo das medias finais 
        double mediafinail=(semestrais [0]+semestrais[1])/2;
        
        //exebição de resultados
        system.out.printf("1°Bimestre:%.1f\n",bimestre[0]);
        system.out.printf("2°Bimestre:%.1f\n",bimestre[1]);
        system.out.printf("1°Semestre:%.1f\n",semestre[0]);
        system.out.printf("2°Semestre:%.1f\n",semestre[1]);
        system.out.printf("3°Bimestre:%.1f\n",trimestre[2]);
        system.out.printf("4°Bimestre:%.1f\n",trimestre[3]);
        system.out.printf("2°Semestre:%.1f\n",semestre[1]);
        system.out.printf("3°Semestre:%.1f\n",semestre[2]);
        system.out.print("Media Final:+ mediafinal");
}
