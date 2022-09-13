# first-partial

Diagrama uml 

dentro del diagrama uml tenemos 3 clases una clase password que se encarga de darle los atributos a las contraseñas una clase validar la cual valida los parametros que deben tener las contraseñas y una clase usuario que crea la contraseña y al final se retorna el contraseña con los parametros ingresados y validados 

UML

class validar {

max_carac:max_carac
min_carac:min_carac

resultado(escr_contra)

}

class usuario{

nombre:string
ID:int

crear_contra(resultado)
escr_contra(password)





}

usuario "1"--"*" password
password --> validar 
@enduml






