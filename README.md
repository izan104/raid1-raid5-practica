# 💽 Práctica RAID 1 y RAID 5

## 📌 Descripción
En esta práctica se implementan y comparan configuraciones RAID 1 y RAID 5 en un entorno de Ubuntu Server ejecutado en VirtualBox. Se analizan sus características, tolerancia a fallos y rendimiento.

---

# 🧪 PART 1 – RAID 1

## 🔧 Creación del RAID 1
Se crean dos discos adicionales en la máquina virtual y se configura un RAID 1 utilizando la herramienta mdadm.

Estado del RAID:
```bash
cat /proc/mdstat
---

**# 🧪 PART 2 – RAID 5**

**## 🔧 Creación del RAID 5**
Se eliminó la configuración anterior de RAID 1 y se creó un nuevo RAID 5 utilizando 4 discos virtuales en Ubuntu Server mediante mdadm.

Estado del RAID:
```bash
cat /proc/mdstat
