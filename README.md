# FloriMundi
Practica de examen usando FloriMundo como ejemplo


JERARQUIA
  - DIRECCION
    -- CONFIDENCIAL
    -- LIBRE
  - CALIDAD
  - OPERATIVA
    -- PRODUCCCION
    -- LOGISTICA
  - COMERCIAL_MARKETING
  - LEGAL

El criterio de jerarquia ha sido mediante Secciones de la logica de negocio y un segun criterio sobre los permisos del documneto.



POSIBLES ETIQUETAS
-SEDE:  espana, kenia, paises_bajos, bolombia , global
- PRODUCTO: lirio, rosa, clavel, orquidea
- TIPO_DOCUMENTO: ficha_tecnica, certificado, contrato, guia-tecnica, pedido
 - TEMPORADA: verano, navidad, invierno
 - ESTADO: borrador, en_revision, en_proceso, archivado, publicado, rechazado 
- SUSTRATOS: sus_tipoC, sus_TipoA

PLANTILLA METADATOS
---
codigo: FM_ES_ROS_2026_001
tipo-doc: 
titulo: Ficha tecnica Rosa del Desierto
sede: espana
version: 1.1
responsables: Juan Gonzalez
fecha_creacion: 01/05/2026
fecha_revision: 02/05/2026
estado: Aprobado
palabra_clave: [rosa, flor, SemillasDeOro, sus_tipoC]
---


NOMENCLATURA
TIPO DE DOCUMENTO: GUIAS TECNICAS DE FLORES
FM_ESROS_2026_001.PDF
He usado la inicial de la empresa
La sede, el codigo de producto ROS=Rosa
año y el numero de version.

FM_CLLIR_2025_034.PDF

TIPO DE DOCUMENTO: PEDIDOS
PEDFM_ES_01052026_009878_0534.PDF
PED pedido + FM Florimundi + Sede + Fecha + nºCliente + nºpedido

PEDFM_PB_05052026_15763_12.PDF



FLUJO DE TRABAJO
- Issue para pedir docuento o modificacion --> tecnico
- Crea una Rama para el documento segun tipo --> nuevas-rosas
- Edita el documento por parte del semillero
- Abre un pull Request (peticion de aprobacion)
- El verificador/responsable Aprueba y hace MERGE
- Le colola la etiqueta de PUBLICADO y lo coloca en la carpeta DOCUMENTOS_PLUBLICOS o la WEB... (ejemplo)

 Estado inicial del documento 
 que actor tiene que hacer 
 Que tiene que hacer (tarea, condiciones, plazo)
 y cual seria el estado siguiente

 Contrato 
 ---Borrador Tecnico de RRHH -- Redactarlo -- EnRevision
 En Reviosion -- Responsable RRHH - Revisar y validar --Aprobado
 Aprobado -- CEO -- Firmar y sellar -- Publico

Estados del Documento = CICLO DE VIDA DEL DOCUMENTO
 BORRADOR
 ENREVISION
 APROBADO
 PUBLICO
 ARCHIVADO
 ELIMINADO (No llegaria a ponerse)
 
                    DIRECTOR      RESPONSABLEAREA      EDITOR        EXTERNO      
 
PEDIDO                VER           VER/EDITAR          CREAR          No

GUIA TECNICA          VER            VER             CREAR/EDITAR      VER

CONTRATO LABORAL      EDITAR          VER                No              No
                      (Aprobar)
