# 🐵🍺 Entre Amigos — Sistema de Tienda

Sistema POS + contabilidad para la tienda física **Entre Amigos** (Cavas · La Pancha Beer).
Venta de cerveza, papas, dulces, gaseosas y más. Una sola página HTML, sin instalación, datos guardados en el navegador (`localStorage`).

## ▶️ Cómo usarlo localmente
1. Abre `index.html` con doble clic (Chrome o Edge recomendado).
2. Inicia sesión:
   - **Administrador** → PIN `1234`
   - **Vendedor** → PIN `1111`
3. ¡Listo! Todo se guarda automáticamente en ese equipo/navegador.

## 👤 Roles

### Administrador
- **📊 Panel**: ventas del día, utilidad, inversión, stock bajo, más vendidos.
- **🛒 Vender**: punto de venta (igual que el vendedor).
- **📦 Inventario**: productos con precio de compra, precio de venta, margen y stock.
- **🚚 Compras**: registra entradas de mercancía (suma stock + inversión).
- **🧾 Ventas**: historial completo de todas las ventas.
- **💰 Contable**: valor de compra, valor de venta, costo de lo vendido, utilidad, saldos, ventas por vendedor/categoría/método de pago. Exporta a CSV y respaldo JSON.
- **👥 Usuarios**: crea/edita vendedores y administradores con su PIN.
- **🧮 Calculadora** y **📢 Publicidad**.

### Vendedor
- **🛒 Vender**: toca productos → carrito → cobra. En **efectivo** indica con cuánto paga el cliente y el sistema calcula **las vueltas** a devolver. También transferencia.
- **🧮 Calculadora**: calculadora de mostrador + calculador rápido de vueltas.
- **🧾 Mis ventas**: lo que ha vendido hoy y en total.

## 🖼️ Logo
El logo es **`assets/logo.svg`** — una versión vectorial mejorada del original (mono con gorra "La Pancha Beer",
jarra de cerveza, "ENTRE AMIGOS", "CAVAS" y el teléfono). Es nítido a cualquier tamaño.
Aparece en login, barra superior y publicidad. Si quieres usar la foto original en su lugar, guárdala como
`assets/logo.svg` (o cambia la extensión en `index.html`).

## 💾 Datos y respaldo
- Todo vive en `localStorage` del navegador de ese equipo.
- Desde **Contable** puedes **Exportar CSV** y **Respaldo JSON**, o **Borrar todo** para reiniciar.

## ☁️ Subir a repositorio
```bash
cd "C:\Users\DEPERAVI\notebooml\tienda-entre-amigos"
git init
git add .
git commit -m "Sistema Entre Amigos — POS + contabilidad"
git branch -M main
git remote add origin <URL-DE-TU-REPO>
git push -u origin main
```
Para publicarlo gratis: GitHub Pages (Settings → Pages → rama `main` / carpeta raíz).

---
Tel. pedidos: **312 777 4605**
