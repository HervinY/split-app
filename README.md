# Split App - Calculadora de Gastos Compartidos

Una aplicación web sencilla y potente para dividir gastos en grupo de forma justa y transparente. Creada para resolver el problema de "¿quién le paga a quién?" después de un almuerzo, una cena o cualquier evento con gastos compartidos.

Esta herramienta permite crear eventos, añadir participantes, registrar quién pagó cada cosa y, con un solo clic, generar un plan de pagos optimizado para que todos queden en paz.

---

### ✨ Características Principales

* **Gestión de Eventos:** Crea múltiples eventos (ej: "Vacaciones en la playa", "Cena del viernes") para mantener las cuentas separadas y organizadas.
* **Participantes Dinámicos:** Añade fácilmente a los amigos que participan en cada evento específico.
* **Registro de Gastos Detallado:** Registra cada gasto con su descripción, monto y la persona que lo pagó.
* **Cálculo de Balances en Tiempo Real:** La aplicación muestra al instante el gasto total, el costo por persona y el balance individual (cuánto ha aportado cada uno vs. lo que debería haber aportado).
* **Liquidación Inteligente:** Genera un plan de pagos simplificado que minimiza el número de transacciones necesarias para saldar todas las deudas.
* **Persistencia de Datos:** Utiliza Firebase Firestore para guardar la información, permitiendo continuar donde lo dejaste o incluso colaborar en tiempo real.

---

### 🚀 Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Estilos:** Tailwind CSS para un diseño moderno y responsivo.
* **Base de Datos:** Firebase Firestore para almacenamiento de datos en tiempo real.
* **Autenticación:** Firebase Authentication (inicio de sesión anónimo/token).

---

### 🔧 Cómo Usar

1.  **Crear un Evento:** Ve a la página principal y crea un nuevo evento con un nombre descriptivo.
2.  **Añadir Amigos:** Dentro del evento, añade los nombres de todos los participantes.
3.  **Registrar Gastos:** Añade cada gasto, asignando quién lo pagó desde el menú desplegable.
4.  **Liquidar:** Una vez registrados todos los gastos, haz clic en el botón "Liquidar Cuentas" para ver el plan de pagos sugerido.
