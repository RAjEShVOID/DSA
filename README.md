public class largestElement {

    public static void main(String[] args) {
        int [] arr = {1,5,28,99,3};
        int result = largest(arr);
        System.out.println(result);
    }

    static int largest (int [] arr){
        int max= Integer.MIN_VALUE;
        for (int i = 0; i < arr.length; i++) {
            if(arr[i] >max){
                max = arr[i];
            }
        }
        return max;
    }
}
