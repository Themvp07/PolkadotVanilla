# Polkadot.js Wallet Connector & Paseo Balance Viewer

Aplicación web para conectar/desconectar una billetera Polkadot.js, mostrar balances en la red Paseo (testnet de Polkadot) y realizar transferencias básicas. Desarrollado como parte del bootcamp **CodeanDOT** de Space4Build.

## 🚀 Características

- **Conexión con Polkadot.js Extension**: Autenticación segura usando la extensión oficial.
- **Visualización de balance**: Muestra saldos de tokens PAS (Paseo) en tiempo real.
- **Transferencias**: Envía tokens PAS a direcciones especificadas.
- **Suscripción a bloques**: Muestra el último bloque de la cadena Paseo.
- **Información del nodo**: Detecta automáticamente la versión del nodo conectado.

## 🛠️ Tecnologías

- **Polkadot.js API**: Conexión con la blockchain vía `@polkadot/api`.
- **ES Modules**: Importación directa desde CDN (sin necesidad de bundlers).
- **Paseo Testnet**: Red de pruebas para desarrolladores Polkadot (`wss://rpc.ibp.network/paseo`).
