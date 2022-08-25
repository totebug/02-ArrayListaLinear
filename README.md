# Lista Linear

Faça um fork deste repositorio e implemente a função buscarElemento

**buscarElemento:**
* Pede para o usuario digitar um numero
* Busca o numero na lista
* Se encontrado exibe a posição do numero na lista
* Se não econtrado exibe "elemento não encontrado" 


void buscarElemento()
{

	int pos = -1;
	int busca=0;

		cout << "Digite o elemento desejado: \n";
		cin >> busca;

		//backup cout << "O valor e': " << busca << endl;

		for (int n = 0; n < nElementos; n++)
		{
			if (busca == lista[n]) {

				cout << "Encontrado pos: " << n << endl;
				pos = n;
			}
		}

		if (pos == -1)
		{
			cout << "Nao encontrado\n" << endl;
		}
}
