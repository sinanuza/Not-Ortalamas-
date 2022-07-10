# Not-Ortalamas-
www.patika.dev Not Ortalması



        public static void main(String[] args) {
        int mat,fiz,tur,kim,muz;
        double avarage;
        Scanner input=new Scanner(System.in);
        System.out.println("matematik notunuz:");
        mat=input.nextInt();
        System.out.println("fizik notunuz:");
        fiz=input.nextInt();
        System.out.println("Turkce notunuz:");
        tur=input.nextInt();
        System.out.println("kimya notunuz:");
        kim=input.nextInt();
        System.out.println("muzik notunuz:");
        muz=input.nextInt();
        if(mat<0||mat>100){
            mat=0;
        }if (fiz<0||fiz>100) {
            fiz=0;
        }if (tur<0||tur>100) {
            tur=0;
        }if (kim<0||kim>100) {
            kim=0;
        }if (muz<0||muz>100) {
            muz=0;
        }
        avarage=(mat+fiz+tur+kim+muz)/5;
        if(avarage<=55){
            System.out.println("Kaldiniz..");
        }else {
            System.out.println("Gectiniz..");
        }
        System.out.println("Notunuz: "+avarage);
    }
}
