# Control de Gastos React

Aplicación web desarrollada con React para la gestión básica de ingresos y gastos personales.

## Demo

https://control-gastos-react-rust.vercel.app/

---

## Características

- Agregar ingresos y gastos
- Eliminar transacciones
- Balance total automático
- Separación entre ingresos y gastos
- Persistencia de datos con LocalStorage
- Interfaz responsive
- Actualización dinámica de la interfaz con React

---

## Tecnologías utilizadas

- React
- JavaScript
- CSS3
- Vite
- LocalStorage

---

## Conceptos implementados

### React Hooks

Uso de:
- useState
- useEffect

para manejo de estado y persistencia de datos.

---

### Componentes reutilizables

La aplicación fue dividida en componentes independientes:

- Balance
- FormularioTransaccion
- ListaTransacciones

---

### Renderizado dinámico

Uso de:
- map()
- props
- renderizado condicional

para mostrar transacciones dinámicamente.

---

### Persistencia de datos

Implementación de LocalStorage para conservar la información incluso después de recargar la página.

---

## Instalación local

Clonar repositorio:

```bash
git clone https://github.com/xavierwork-p/control-gastos-react.git
```

Entrar al proyecto:

```bash
cd control-gastos-react
```

Instalar dependencias:

```bash
npm install
```

Ejecutar proyecto:

```bash
npm run dev
```

---

## Autor

Xavier Peralta
