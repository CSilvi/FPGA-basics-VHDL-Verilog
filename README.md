# FPGA-basics-VHDL-Verilog

---

/src → Código fuente (VHDL/Verilog)
/tb → Testbenches
/docs → Documentación y apuntes
/examples → Casos de uso y proyectos simples

## ⚙️ Componentes básicos incluidos

### 🔹 Lógica combinacional
- Puertas lógicas (AND, OR, NOT, XOR, etc.)
- Multiplexores (2:1, 4:1, parametrizables)
- Demultiplexores
- Codificadores y decodificadores
- Comparadores de magnitud

### 🔹 Lógica secuencial
- Flip-Flops (D, T, JK, SR)
- Latches
- Registros de desplazamiento
- Contadores (binarios, BCD, ascendentes, descendentes, con carga)
- Máquinas de estados finitos (FSM: Moore y Mealy)

### 🔹 Temporización y control
- Divisores de reloj
- Generadores de pulso
- Debouncers para pulsadores
- Watchdog timer básico

### 🔹 Memorias
- ROM simple
- RAM (single-port y dual-port)
- FIFO síncrono y asíncrono
- Shift-register FIFO

### 🔹 Interfaces de comunicación
- UART Tx/Rx
- SPI Master/Slave
- I2C básico
- Handshake genérico (valid/ready)

### 🔹 DSP / procesamiento de datos
- Sumadores/restadores (con y sin acarreo)
- Multiplicadores
- Acumuladores
- Filtros FIR simples
- PWM

---

## 🛠️ Herramientas recomendadas
- **Vivado** (Xilinx)
- **Quartus** (Intel/Altera)
- **GHDL + GTKWave** (simulación open source)
- **Icarus Verilog** (para módulos en Verilog)

---

## 🎯 Objetivo
- Reforzar fundamentos de diseño digital aplicado a FPGAs.  
- Disponer de una librería de módulos básicos reutilizables.  
- Practicar la escritura clara y documentada en VHDL/Verilog.  
- Mantener ejemplos con **testbench asociado** para cada componente.  

---

## 📖 Recursos útiles
- [Free Range VHDL](https://freerangefactory.org/freerange-vhdl/)
- [nandland.com FPGA tutorials](https://nandland.com)
- [asic-world.com Verilog tutorials](http://asic-world.com/verilog/index.html)

---

✍️ *Siéntete libre de clonar, practicar, y ampliar este repo con tus propios módulos.*
