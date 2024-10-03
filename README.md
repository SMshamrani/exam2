# exam2
//Sarah Alshamrani
//444003567-------

class LinearSearch {
    static int s(int a[], int b, int c) {
        for (int d = 0; d < b; d++) {
            if (a[d] == c)
                return d;  }
        return -1;  }

    public static void main(String[] args) {
        int[] e = { 3, 4, 1, 7, 5 };
        int f = e.length;
        int g = 4;
        int h = s(e, f, g);
        if (h == -1)
            System.out.println("Element is not present in the array");
        else
            System.out.println("Element found at position " + h);  } } //--------------------------------------------------------------------
