# To generate the base protobuf sparkplug_b Python library
protoc -I=../../sparkplug_b/ --python_out=. ../../sparkplug_b/sparkplug_b.proto 


Instruções Henrique ->

-> Este cógigo foi baixado do link: https://github.com/eclipse/tahu/tree/master/python
-> Foram feitas adaptações para conseguir fazer funcionar.
-> O arquivo sparkplugPub.py é o publicador. Retirado da pasta exemplos e efetuada algumas modificações.
-> Foi utilizado a versão do Python 3.7. A biblioteca Protobuf deve ser instalada com a versão igual ou inferior a 3.20.