# 👤 UserSearchApp

Una pequeña aplicación desarrollada en **SwiftUI**. Permite buscar usuarios por nombre desde un servicio mock, mostrar resultados en una lista y navegar a una vista de detalle.

---

## 🚀 Características

- 🔍 Búsqueda de usuarios por nombre
- 📄 Listado con nombre y correo electrónico
- 👁 Detalle de usuario: nombre, correo, dirección y teléfono
- 🔄 Indicador de carga y manejo de errores
- ✅ Pruebas unitarias para el ViewModel
- 🎨 UI moderna con SF Symbols y diseño responsivo

---

## 🧪 Tecnología

- `Swift 5`
- `SwiftUI`
- `MVVM Architecture`
- `XCTest` para pruebas unitarias

---

## 🧰 Instalación

1. Clona este repositorio:
   git clone https://github.com/tuusuario/UserSearchApp.git
2.	Abre UserSearchApp.xcodeproj o UserSearchApp.xcworkspace en Xcode.
3.	Ejecuta el proyecto en el simulador (Cmd + R).
4.	Ejecuta las pruebas unitarias (Cmd + U).

🧪 Pruebas

El archivo UserSearchViewModelTests.swift contiene pruebas para verificar:
	•	Búsqueda con resultados
	•	Búsqueda sin coincidencias
	•	Evitar búsquedas vacías

Puedes correrlas desde Xcode o con:

Cmd + U

📁 Estructura del proyecto

UserSearchApp
│
├── Models/
├── ViewModels/
├── Views/
├── Services/
└── Tests/

📌 Notas adicionales
	•	El servicio de usuarios está mockeado localmente en memoria.
	•	No se necesita conexión a internet para ejecutar el proyecto.
	•	El diseño está optimizado para modo claro y oscuro.

⸻

🧑‍💻 Autor

Raúl Leonardo Pavón Toral
