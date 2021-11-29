# HelloWorld
Hola

# ITC
## Hugo Alvarado
### A00834109

**bold text**

*italicized text*

> Eset es un trabajo de clase

1. First item
2. Second item
3. Third item

- First item
- Second item
- Third item

`code`

class HelloWorld{
private:
  int holas = 15;
  string saludo = "Buenas buenas";
public:
  void gethHolas();

};


[title](TAREA 29)

![alt text](Yasuo_True_Damage_EP.png)

#Codigo para leer las series - //Input file stream - leer del in

'ifstream lectura; 
string linea, dato;
lectura.open("Series.csv",ios::in);
while (getline(lectura, linea))
{
    //la linea que se leyo se muestra
    cout << linea << endl;
    stringstream registro(linea);
    
    for (int columna = 0; getline(registro, dato, ','); ++columna)
    {
        switch (columna)
        {
            case 0: // ID
                iD = dato;
            break;
            case 1: // NOMBRE
                titulo = dato;
            break;
            case 2: // APELLIDO
                duracion  = std::stoi(dato);
            break;
            case 3: // EDAD
                genero = dato;
            break;
            case 4: // PROMEDIO
                calificacionPromedio = std::stod(dato);
            break;
             case 5: // PROMEDIO
                cantEpisodios = std::stoi(dato);
            break;
    }

}
cout <<iD<<","<<titulo<<","<<duracion<<","<<genero<<","<<calificacionPromedio<< "," << cantEpisodios <<"\n";

}
return 0;
'
