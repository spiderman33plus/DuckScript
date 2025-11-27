## 📝 Cómo usar DuckScript

### Ejecutar scripts

```bash
python duck_interpreter.py archivo.duck

let nombre = "Juan"
input edad "Escribe tu edad:"
if edad >= 18:
    print "Mayor de edad"
else:
    print "Menor de edad"
end


window "Mi App" 400 300
label "Escribe tu nombre:" 50 50
entry nombre 50 80
button "Saludar" 50 120:
    message "Hola " + nombre
end



