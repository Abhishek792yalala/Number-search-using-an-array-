# Number-search-using-an-array-
class Java{

    //To search the number in an array

    public static void main(String... args){

        System.out.println("Welcome to java programming");

        int arr[]={1,2,3,4}; int num=1;

        for(int element:arr){

            if(num==element){

               System.out.println("Number is in array");

                break;

            }

            else{

                System.out.println("Number is not in array");

                break;

            }

        }

    }

}

    Welcome to java programming

    Number is in array
