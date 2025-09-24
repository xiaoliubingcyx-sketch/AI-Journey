1、梯度下降
梯度下降策略的目的是为自动找到使得cost最低的weight、bias（coefficient）。
w = w - α ( dJ/dw )
b = b - α ( dJ/db )
每次都沿着最快上升的反方向走一步，步长由α控制。
