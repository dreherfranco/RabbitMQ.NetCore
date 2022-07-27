Procedimiento para ver la ejecucion de las tareas:

Abrir consola 1:
# shell 1
cd Worker
dotnet run
# => Press [enter] to exit.


Abrir consola 2:
# shell 2
cd Worker
dotnet run
# => Press [enter] to exit.


Abrir consola 3:
# shell 3
cd NewTask
dotnet run "First message."
dotnet run "Second message.."
dotnet run "Third message..."
dotnet run "Fourth message...."
dotnet run "Fifth message....."


En consola 1 veremos como resultado:
# shell 1
# => Press [enter] to exit.
# => [x] Received First message.
# => [x] Done
# => [x] Received Third message...
# => [x] Done
# => [x] Received Fifth message.....
# => [x] Done

En consola 2 veremos como resultado:
# shell 2
# => Press [enter] to exit.
# => [x] Received Second message..
# => [x] Done
# => [x] Received Fourth message....
# => [x] Done