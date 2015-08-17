# flaca
cosas

recordschile (Stack S)
{
	int cantidad=0;
	stack P;
	stack chile;
	while(!s.empty())
	{
		elemento = S.pop();
		if (elemento.pais == 'Chilean')
		{
			cantidad ++;
			elem=elemento;
			chile.push(elem);
		}
		P.push(elemento);
	}
	cout<<"Las pruebas que tubieron record por chilenos son:"<<endl;
	while(!chile.empty())
	{
		elemento=chile.pop();
		cout<<elemento.nomprueba<<endl;
	}
	while(!p.empty())
	{
		elemento=p.pop();
		S.push(elemento);
	}
	return cantidad;
}
