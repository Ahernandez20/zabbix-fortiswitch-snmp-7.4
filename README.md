# Zabbix Template: FortiSwitch SNMP

Monitoreo inteligente y escalable de **FortiSwitches gestionados por FortiGate** mediante **SNMPv3**, diseñado para entornos empresariales con cientos de dispositivos.

## ✨ Características

- ✅ **Descubrimiento automático** de switches y puertos.
- ✅ **Alertas inteligentes**: solo notifica si un puerto **activo se cae** (ignora puertos siempre libres).
- ✅ **Nombres claros**: `Switch SERIAL port5: Status`.
- ✅ **Seguro**: compatible con **SNMPv3** (cifrado obligatorio).
- ✅ **Escalable**: funciona en entornos con **200+ FortiGates** sin configuración manual por puerto.
- ✅ **Totalmente automático**: sin macros ni intervención humana.

## 📥 Cómo usar

1. **En Zabbix**:
   - Ve a **Configuration → Templates → Import**.
   - Sube el archivo: (templates/FortiSwitch_SNMP.yaml)
2. **En tu host FortiGate**:
   - Asegúrate de que la interfaz SNMP tenga **timeout = 30s**.
   - Usa tus credenciales SNMPv3 existentes.
3. **¡Listo!** El template descubrirá switches y puertos automáticamente.

## ⚙️ Requisitos

- Zabbix **7.0 o superior**
- FortiGate con **FortiOS 7.0+** y FortiSwitches gestionados por **FortiLink**
- SNMPv3 habilitado en el FortiGate

## 📜 Licencia

Este template es de uso libre. Puedes modificarlo y redistribuirlo.
