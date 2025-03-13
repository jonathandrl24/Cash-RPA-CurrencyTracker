# Cash Currency Tracker (Automatización UiPath)  

## 📌 Objetivo  
Automatizar la obtención diaria de tasas de cambio USD/EUR a COP y generar reportes estructurados en Excel para la empresa Cash, optimizando sus operaciones financieras.  

## 🚀 Características Principales  
- **Daily Automation Workflow**: Proceso programado en UiPath con:  
  - Conexión a fuentes oficiales (Banco de la República, Dólar Today, etc.)  
  - Procesamiento de datos en tiempo real  
  - Exportación a Excel con formato predefinido  
- **Historical Data Manager**:  
  - Almacenamiento en archivos .xlsx con marca temporal  
  - Dashboard integrado con gráficos temporales  
- **Error Handling System**:  
  - Reintentos automáticos ante fallos de conexión  
  - Registro detallado de logs en .txt  

## ⚙️ Configuración  
1. Requiere **UiPath Studio 2023+**  
2. Dependencias:  
   - Paquete `UiPath.Excel.Activities`  
   - Paquete `UiPath.WebAPI.Activities`  
3. Configurar archivo `Config.json` con:  
   - Rutas de guardado  
   - Horarios de ejecución  
   - Fuentes de datos  

## 📄 Licencia  
MIT License - Libre para uso y modificaciones, citando la autoría original.  
