O usuário entrará com 2 vetores de 6 posições e iremos exibir a união destes dois na tela em um terceiro vetor

Instale o Dev++; Sistema operacional windows; Desenvolvido em C++ Autor: Ismael Data: 01-12-2021

classe / metodo 
class uniao{ 
	int vet[6]; 
	int vet1[6];
	int vet2 [12];
	int i;
public:
vets(int vet[6]);
};

entrada de valores 
int uniao::vets(int vet[6]){
for (i=0;i<6;i++){
    cout << "Digite o " << i+1 << " primeiro array"<< endl;
    cin >> vet[i];
}
for (i=0;i<6;i++){
    cout << "Digite o " << i+1 << " segundo array"<< endl;
    cin >> vet1[i];

saida de valores 
for (i=0;i<6;i++){
    vet2[i] = vet[i];
}
    for ( i = 6; i < 12; i++ )
        vet2[i] = vet1[i-6];

         for ( i = 0; i < 12; i++ )
        cout<< vet2[i] << " ";
    }

saida dos valores
int main(){
    int vet[6];
uniao vettt;
vettt.vets(vet);
return 0;
}
