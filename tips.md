h1 {
            /* "Sé tan grande como el 5% de la pantalla, PERO nunca bajes de 1.5rem, ni superes los 3rem" */
            font-size: clamp(1.5rem, 5vw, 3rem);
            }

img {
            max-width: 100%; /* "Puedes achicarte al 50%, pero jamás crecer más del 100% de tu contenedor" */
            height: auto; /* Mantén tu relación de aspecto, no te deformes */
            object-fit: cover; /* Si te obligo a medir 200x200, recórtate con elegancia en vez de aplastarte */
            }

/* Si el sistema del usuario le pide modo oscuro a las apps... */
@media (prefers-color-scheme: dark) {
    body {
        background-color: #121212; /* Apagamos la luz del fondo */
        color: #e0e0e0; /* Volvemos las letras grises claro */
    }
}

función clamp()

usar BEM para darle nombre a las etiquetas de CSS


