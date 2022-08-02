Para loguear errors y warnings:
	cd ReceiveLogsDirect
	dotnet run warning error > logs_from_rabbit.log

Para solo mostrar en consola:
	cd ReceiveLogsDirect
	dotnet run info warning error

Emitir un log de error:
	cd EmitLogDirect
	dotnet run error "Run. Run. Or it will explode."