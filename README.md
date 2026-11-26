# Laboratorios de Cisco Modeling Labs (CML)

Guías de laboratorio y videos de Merlin Programs para instalar y usar Cisco Modeling Labs (CML-Free 2.10) en una laptop con Windows.

Haz los laboratorios en orden: cada uno parte de lo que dejó listo el anterior.

## Guías

| N.° | Laboratorio | Qué aprendes |
| --- | --- | --- |
| 1 | [Instalar Cisco Modeling Labs (CML-Free)](guias/Laboratorio_1_Instalar_CML.pdf) | Preparar Windows, crear la máquina virtual en VMware Workstation, instalar CML y entrar a la interfaz web. |
| 2 | [Topología entre dos sedes](guias/Laboratorio_2_Topologia_CML.pdf) | Armar una red con dos routers, dos switches y dos PC; configurar direcciones IP y rutas estáticas, y probar la conectividad. |
| 3 | [Conectar Claude a CML con MCP](guias/Laboratorio_3_MCP_CML.pdf) | Instalar el servidor `cml-mcp` y pedirle a Claude que cree y revise laboratorios en CML. |

## Videos

| Video | Laboratorio relacionado |
| --- | --- |
| [Topología R1-R2 en CML 2.10, en movimiento](videos/Laboratorio_R1-R2_CML_2.10_en_movimiento.mp4) | Laboratorios 2 y 3 |

Se abre en el navegador; para guardarlo, usa el botón de descarga.

## Descargas

Cada estudiante descarga los instaladores con su propia cuenta, desde el sitio oficial. Este repositorio no los incluye: son software de Cisco y de Broadcom, y sus licencias no permiten redistribuirlos.

| Archivo | Dónde se descarga | Tamaño aproximado |
| --- | --- | --- |
| `cml2_f_<versión>_amd64.ova` (máquina virtual de CML-Free) | [Cisco Software Download · CML-Free](https://software.cisco.com/download/home/286193282/type/286326381/release/CML-Free), con tu cuenta de Cisco o de Networking Academy | 1,3 GB |
| `refplat-<fecha>-free-iso.zip` (imágenes de routers, switches y PC) | La misma página de Cisco | 3 GB |
| VMware Workstation Pro | Portal de soporte de Broadcom, artículo «Download and license information for VMware Workstation» (sin costo, requiere cuenta) | 300 MB |

Los pasos detallados están en la Parte 2 y la Parte 4 del Laboratorio 1.

## Requisitos

- Laptop con Windows 10 u 11 de 64 bits y procesador Intel o AMD con virtualización; se recomiendan 16 GB de RAM y 80 GB libres en un disco SSD.
- Cuenta en Cisco.com (sirve la de Networking Academy) y cuenta en el portal de soporte de Broadcom para descargar VMware Workstation Pro sin costo. Los enlaces están en el Laboratorio 1.
- Para el Laboratorio 3: Claude Desktop para Windows con tu cuenta de Claude.

CML no funciona en Mac con chip Apple (M1 a M4): avisa a tu instructor para usar un equipo del laboratorio.

## Uso del material

Este repositorio es de solo lectura: puedes ver y descargar las guías, pero no modificarlas. Si encuentras un error, avísale a tu instructor.

© 2026 Merlin Programs. Todos los derechos reservados. Cisco, Cisco Modeling Labs y Cisco Networking Academy son marcas de Cisco Systems, Inc.
