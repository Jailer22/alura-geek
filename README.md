Deploy JSON Server a Vercel
Una plantilla para desplegar JSON Server en Vercel, permitiéndote ejecutar una API REST falsa en línea 🐣.

Cómo usar
Haz clic en "Use this template" o clona este repositorio.
Actualiza o usa el archivo db.json predeterminado en el repositorio.
Regístrate o inicia sesión en Vercel.
Desde el panel de Vercel, haz clic en "+ New Project" y luego en "Import" tu repositorio.
En la pantalla "Configure Project", deja todo como predeterminado y haz clic en "Deploy".
Espera hasta que se complete el despliegue, y tu servidor JSON personalizado estará listo para servir.
db.json predeterminado
json
Copiar
{
  "product": [
    {
      "img": "https://example.com/product1.png",
      "name": "Product 1",
      "price": "$100.000",
      "description": "Description for Product 1",
      "category": "category1",
      "id": 1
    },
    {
      "img": "https://example.com/product2.png",
      "name": "Product 2",
      "price": "$20.000",
      "description": "Description for Product 2",
      "category": "category2",
      "id": 2
    }
  ]
}
Construye tú mismo
Si deseas crear el proyecto desde cero, puedes seguir los pasos a continuación:

Crea un nuevo repositorio y clónalo.
Ejecuta npm init -y para generar el archivo package.json.
Instala json-server y cors con npm install json-server cors.
Crea el archivo db.json con tus datos.
Crea el archivo api/server.js con la configuración del servidor.
Crea el archivo vercel.json con la configuración de Vercel.
Realiza un commit y sube los cambios a tu repositorio.
Conecta tu repositorio a Vercel y despliega el proyecto.
Asegúrate de tener paciencia, ya que puede tomar unos minutos para que el despliegue esté listo.