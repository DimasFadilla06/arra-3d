# arra-3d

#include <iostream>

using namespace std;

int main()
{
    //arr 3d
  
    int angka[2][3][2]={{{10,15},{20,25},{30,35}},
    {{40,45},{50,55},{60,65}}};

 //Memanggil array
 for(int i = 0; i<=1; i++){
  cout<<i+1<<".\n";
  for(int j = 0; j<=2; j++){
   cout<<j+1<<".";
   for(int k = 0; k<=1; k++){
    cout<<" "<<angka[i][j][k]<<"\t\t ";
   }
   cout<<endl;
  }
  cout<<endl;
 }
    return 0;
}
