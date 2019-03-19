# fractol

2nd project of the Graphic Branch of UNIT Factory (42 school). Fractol is a project aimed at exploring fractals, mathematical sets that exhibit a repeating pattern displayed at every scale.

**Features**
1. Render different fractals: mandelbrot, julia, burning ship, spider, tricorn and newton
2. Different color schemes
3. Multithreaded renderer
4. The mouse wheel zooms in and out, almost infinitely (within the limits of the computer)
5. It is possible to make the parameter of the Julia set vary only with the mouse (without clicking)

# Project Details

This project is written for macOS (OS X High Sierra) using *MinilibX* graphic library (https://github.com/abouvier/minilibx) and it is needed to run this project

# Usage

```
git clone https://github.com/kmieshko/fractol.git
cd fractol
make
./fractol [Mandelbrot, Julia, Sheep, Newton, Spider - choose one]
```

# Some examples

**Mandelbrot**:

<p align="center"><img src="https://github.com/kmieshko/fractol/blob/master/examples/mandelbrot.png" width=600></p>

**Julia**:

<p align="center"><img src="https://github.com/kmieshko/fractol/raw/master/examples/julia.gif" width=600></p>

**Burning Sheep**:

<p align="center"><img src="https://github.com/kmieshko/fractol/blob/master/examples/sheep.png" width=600></p>

**Spider**:

<p align="center"><img src="https://github.com/kmieshko/fractol/blob/master/examples/spider.png" width=600></p>

**Newton**:

<p align="center"><img src="https://github.com/kmieshko/fractol/blob/master/examples/newton.png" width=600></p>

# Disclaimer

This project is written according to 42's "The Norm" which specifies special rules for code like less then 25 lines in each function, 85 symbols in line, forbidden most of libraries and functions that wasn't written by you, also "for", "switch case" and others are forbidden (you can read more at https://ncoden.fr/datas/42/norm.pdf)


