


# LOG AUDITORIA TRANSACCIONES APP
## Formato log:
fecha,hora,tipotransaccion,cuenta_origen,cuenta_destino,monto,estado

>2024-07-01 10:00:00,deposito,12345,,1000.00,exito
2024-07-01 10:05:00,retiro,12345,,200.00,exito
2024-07-01 10:10:00,transferencia,12345,67890,500.00,exito
2024-07-01 10:15:00,deposito,67890,,1500.00,exito
2024-07-01 10:20:00,retiro,67890,,300.00,fallo
2024-07-01 10:25:00,transferencia,67890,12345,1000.00,exito

