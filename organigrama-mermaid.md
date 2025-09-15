# ORGANIGRAMA VISUAL - BARRIOCONECTADO RD

## Diagrama de la Estructura Organizacional

```mermaid
graph TD
    A[DIRECTOR GENERAL] --> B[DIRECTOR TÉCNICO]
    A --> C[DIRECTOR COMERCIAL]
    A --> D[DIRECTOR ADMINISTRATIVO]
    
    B --> E[GERENTE DE DESARROLLO]
    B --> F[GERENTE DE INFRAESTRUCTURA]
    
    E --> G[DESARROLLADORES FULL-STACK]
    E --> H[ESPECIALISTAS QA]
    E --> I[ESPECIALISTAS UX/UI]
    
    F --> J[ESPECIALISTAS DEVOPS]
    F --> K[ESPECIALISTAS SEGURIDAD]
    F --> L[ANALISTAS DE DATOS]
    
    C --> M[GERENTE DE VENTAS]
    C --> N[GERENTE DE MARKETING]
    
    M --> O[EQUIPO VENTAS]
    M --> P[EQUIPO ATENCIÓN AL CLIENTE]
    
    N --> Q[ESPECIALISTAS MARKETING]
    N --> R[ESPECIALISTAS COMUNICACIÓN]
    
    D --> S[GERENTE DE RRHH]
    D --> T[GERENTE DE FINANZAS]
    D --> U[GERENTE DE OPERACIONES]
    
    S --> V[ESPECIALISTAS RRHH]
    S --> W[ESPECIALISTAS LEGALES]
    
    T --> X[CONTADORES]
    T --> Y[ANALISTAS FINANCIEROS]
    
    U --> Z[ESPECIALISTAS PROCESOS]
    U --> AA[ESPECIALISTAS CALIDAD]
```

## Descripción de Equipos por Área

### Área Técnica
- **Desarrolladores Full-Stack:** React/TypeScript, Node.js/Express
- **Especialistas QA:** Playwright, Jest, Testing automatizado
- **Especialistas UX/UI:** Diseño de interfaz, experiencia de usuario
- **Especialistas DevOps:** AWS, Docker, CI/CD
- **Especialistas Seguridad:** Ciberseguridad, compliance
- **Analistas de Datos:** Big Data, reportes, dashboards

### Área Comercial
- **Equipo Ventas:** Cierre de contratos, relaciones con clientes
- **Equipo Atención al Cliente:** Soporte técnico, capacitación
- **Especialistas Marketing:** Branding, comunicación digital
- **Especialistas Comunicación:** Relaciones públicas, eventos

### Área Administrativa
- **Especialistas RRHH:** Reclutamiento, desarrollo organizacional
- **Especialistas Legales:** Contratos, compliance, regulaciones
- **Contadores:** Contabilidad, facturación, impuestos
- **Analistas Financieros:** Presupuestos, proyecciones, inversiones
- **Especialistas Procesos:** Mejora continua, optimización
- **Especialistas Calidad:** ISO, auditorías, certificaciones

## Flujo de Comunicación

```mermaid
graph LR
    A[CLIENTE] --> B[ATENCIÓN AL CLIENTE]
    B --> C[GERENTE DE VENTAS]
    C --> D[DIRECTOR COMERCIAL]
    D --> E[DIRECTOR GENERAL]
    
    F[DESARROLLADOR] --> G[GERENTE DE DESARROLLO]
    G --> H[DIRECTOR TÉCNICO]
    H --> E
    
    I[ANALISTA FINANCIERO] --> J[GERENTE DE FINANZAS]
    J --> K[DIRECTOR ADMINISTRATIVO]
    K --> E
```

## Matriz de Responsabilidades

| Área | Responsabilidad Principal | Responsabilidad Secundaria |
|------|-------------------------|---------------------------|
| Técnica | Desarrollo del producto | Soporte técnico |
| Comercial | Ventas y marketing | Atención al cliente |
| Administrativa | Gestión interna | Compliance legal |
| General | Estrategia y dirección | Relaciones institucionales |