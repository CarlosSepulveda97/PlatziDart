void main() {
  var NumeroMenor = 0;
  var NumeroMayor = 0;
  var Promedio = 0.0;
  var LargoLista = 0;

  var list = [33, 15, 27, 40, 22];

  for (var i in list) {
    LargoLista++;
    Promedio += i;

    if (NumeroMayor < i) {
      NumeroMayor = i;
    }
  }

  NumeroMenor = NumeroMayor;
  for (var e in list) {
    if (e < NumeroMenor) {
      NumeroMenor = e;
    }
  }

  Promedio = Promedio / LargoLista;

  print("Numero menor: " + NumeroMenor.toString());
  print("Numero mayor: " + NumeroMayor.toString());
  print("Promedio: " + Promedio.toString());
}
