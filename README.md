```mermaid
graph TD
    A[开始] --> B{条件判断}
    B -- 是 --> C[操作 1]
    B -- 否 --> D[操作 2]
    C --> E[结束]
    D --> E
