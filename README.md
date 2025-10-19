#include <iostream>
using namespace std;

// Fonksiyon tanımı: iki sayı alır, küçük olanı döndürür
int kucukBul(int sayi1, int sayi2) {
    if (sayi1 < sayi2)
        return sayi1;
    else
        return sayi2;
}

int main() {
    int a, b;
    cout << "Iki sayi giriniz: ";
    cin >> a >> b;

    cout << "Kucuk olan sayi: " << kucukBul(a, b) << endl;

    return 0;
}
