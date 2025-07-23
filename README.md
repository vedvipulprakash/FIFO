# FIFO


A Synchronous FIFO (First-In-First-Out) is a hardware buffer used to temporarily store data between producer and consumer modules operating under the same clock domain.
| Signal    | Description                           |
| --------- | ------------------------------------- |
| `clk`     | Common system clock                   |
| `rst_n`   | Active-low reset                      |
| `cs`      | Chip select (enables FIFO operations) |
| `wr_en`   | Write enable                          |
| `rd_en`   | Read enable                           |
| `data_in` | Data input for write operation        |
| Signal     | Description                    |
| ---------- | ------------------------------ |
| `data_out` | Data output for read operation |
| `empty`    | High when FIFO is empty        |
| `full`     | High when FIFO is full         |
