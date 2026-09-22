riscv-uvm-verification/
│
├── rtl/
│   ├── uart/
│   ├── timer/
│   ├── gpio/
│   └── soc/
│
├── tb/
│   ├── agents/
│   │   ├── axi_agent/
│   │   ├── uart_agent/
│   │   └── gpio_agent/
│   │
│   ├── sequences/
│   ├── scoreboard/
│   ├── coverage/
│   ├── ral/
│   ├── assertions/
│   └── tests/
│
├── sim/
├── scripts/
├── regress/
├── docs/
└── README.md

SystemVerilog
      ↓
UVM basics
      ↓
AXI4-Lite
      ↓
Scoreboard + coverage
      ↓
Assertions
      ↓
RAL
      ↓
RISC-V subsystem
      ↓
Regression/CI
      ↓
FPGA validation
      ↓
Python / PSS / formal / AI-assisted verification