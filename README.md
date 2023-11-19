csharp
using System;

class Program
{
    static void Main()
    {
        // Medidas de seguridad predefinidas
        string[] medidasSeguridad = {
            "Control de acceso físico",
            "Firewall de red",
            "Antivirus actualizado",
            "Respaldo regular de datos",
            "Políticas de contraseñas fuertes",
            "Capacitación en seguridad para empleados",
            "Monitoreo de actividad sospechosa",
            "Actualización de software regular",
            "Auditorías de seguridad periódicas",
            "Plan de respuesta a incidentes"
        };

        // Mostrar las medidas predefinidas
        Console.WriteLine("Medidas de seguridad predefinidas:");
        for (int i = 0; i < medidasSeguridad.Length; i++)
        {
            Console.WriteLine($"{i + 1}. {medidasSeguridad[i]}");
        }

        // Pausa para ver los resultados
        Console.ReadLine();
    }
}
