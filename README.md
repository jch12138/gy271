<!--
 * @Author: your name
 * @Date: 2020-01-10 10:52:06
 * @LastEditTime : 2020-01-10 13:36:19
 * @LastEditors  : Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /stm32f407-atk-explorer/gy271/README.md
 -->
# GY271

## 简介

GY271 采用 HMC5843 芯片,HMC5843 采用霍尼韦尔的各向异性磁阻(AMR)技术，这一技术带来的好处是其他磁传感器技术无法企及的。这些传感器的主 要特点在于轴向高灵敏度和线性、固相结构、垂直轴间低灵敏度，用于测量地球磁场的方向和磁力，从十万分之几高斯到 6 高斯(gauss)。 霍尼韦尔的磁传感器位于行业内灵敏度最高和可靠性最好的低强度磁场传感器之列。



## 参数

输入电压: 3-5v.

通信方式: IIC 通信协议

测量范围: ±1.3-8Ga



## 支持情况

| 包含设备     | 磁力计 |
| ------------ | ------ |
| 通讯接口     |        |
| IIC          | √      |
| 工作模式     |        |
| 轮询         | √      |
| 中断         |        |
| FIFO         |        |
| 数据输出速率 |        |
| 数据测量范围 |        |
| 自检         |        |

## 使用说明

### 依赖

* RT-Thread 4.0.0+
* Sensor 组件
* IIC 驱动

### 获取软件包

### 使用软件包

### 注意事项

### 联系人信息

维护人:

* [jch12138](https://github.com/jch12138)
* 主页: [https://github.com/jch12138/gy271](https://github.com/jch12138/gy271)