# VisualFoxPro

Obtener datos de un TextBox
```
Float(Val(txtNum1.Value))
```

Como sumar dos números
```
ThisForm.txtResultado.Value = Float(Val(txtNum1.Value)) + Float(Val(txtNum2.Value))
```

Como restar dos números
```
ThisForm.txtResultado.Value = Float(Val(txtNum1.Value)) - Float(Val(txtNum2.Value))
```

Como restar dos números
```
ThisForm.txtResultado.Value = Float(Val(txtNum1.Value)) * Float(Val(txtNum2.Value))
```

Como restar dos números
```
ThisForm.txtResultado.Value = Float(Val(txtNum1.Value)) / Float(Val(txtNum2.Value))
```

Sentencias IF ELSE
```
LOCAL age 

age = 20

IF age >= 21 THEN
  Messagebox("Eres mayor de edad")
ELSE
  Messagebox("Eres mayor de edad")
ENDIF
```

Obtener Fecha
```
Date()
```

Obtener Fecha y Hora
```
DateTime()
```

Dia de la semana
```
DOW(Date())
```

Longitud de un Array
```
ALEN(myArray)
```

Operador Ternario en VFP
```
IIF(nEdad < 18, "¡Eres menor de edad!", "¡Eres mayor de edad!")
```

Bloque With
```
WITH <Objecto>
  <Propiedades a modificar>
ENDWITH
```
