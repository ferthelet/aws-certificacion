# Certified Solutions Architect - Associate (SAA-C03)

## AWS Well Architected Framework (WAF)

- El marco AWF proporciona un enfoque coherente para evaluar arquitecturas de nube y orientacion para implementar disenios
- AWF se organiza en 6 pilares: seguridad, eficiencia del rendimiento, confiabilidad, excelencia operativa, optimizacion de costos y sustentabilidad
- Cada pilar documenta una serie de preguntas basicas  que le permiten comprender si una arquitecturta determinada esta alineada con las practicas recomendadas de la nube
- Permite revisar el estado de las cargas de trabajo y las compara con las practicas recomendada mas recientes de AWS

### Seguridad

1. Base de identidad
2. Trazabilidad
3. Seguridad en todas las capas
4. Evaluacion de riesgos

[Documento tecnico sobre seguridad](https://d1.awsstatic.com/whitepapers/architecture/AWS-Security-Pillar.pdf)

### Eficiencia del rendimiento

1. Elegir recuros eficientes y mantener la eficiencia con los cambios de la demanda
2. Democratixzar las tecnologias avanzadas
3. Emplear la "compatiibilidad mecanica", por ejemplo tener en cuenta los patrones de acceso cuando se implementa una BBDD

[Documento tecnico sobre eficiencia del rendimiento](https://d1.awsstatic.com/whitepapers/architecture/AWS-Performance-Efficiency-Pillar.pdf)

### Confiabilidad

1. Recuperarse con rapidez de errores en la infra o interrupciones de servicio
2. Adquirir dinamicamente los recursos TI para satisfacer la demanada
3. Mitigar interrupciones
   - errores de configuracion
   - problemas transitorios de red
  
[Documento tecnico sobre confiabilidad](https://d1.awsstatic.com/whitepapers/architecture/AWS-Reliability-Pillar.pdf)

### Excelencia operativa

1. Implementar sistemas
2. Ejecutar, operar el sistema
3. Supervisar sistemas

[Documento tecnico sobre excelencia operativa](https://d1.awsstatic.com/whitepapers/architecture/AWS-Operational-Excellence-Pillar.pdf)

### Optimizacion de costos

1. Medir le eficiencia
2. Eliminar gastos innecesarios
3. Considerar el uso de servicios adminsitrados

[Documento tecnico sobre optimizacion de costos](https://d1.awsstatic.com/whitepapers/architecture/AWS-Cost-Optimization-Pillar.pdf)

### Sostenibilidad

1. Comprender el impacto
2. Establecer objetivos de sostenibilidad
3. Maximizar la utilizacion
4. Anticipar y adoptar nuevas tecnologias mas eficientes
5. Reducir el impacto descendente de sus cargas de trabajo en la nube

[Documento del pilar de sostenbilidad](https://docs.aws.amazon.com/wellarchitected/latest/sustainability-pillar/sustainability-pillar.html)


## Consideracion de disenio

- Habilite escalabilidad
- Automatice su entorno
- Trate los recursos como desechables
- Utilice componentes de acoplamiento debil
- Disenie servicios, no servidores
- Elija la solucion de bbdd adecuada
- Minimice los puntos unicos de error
- Optimice el costo
- Use el almacenamiento en cache
- Proteja la infrastructura completa

