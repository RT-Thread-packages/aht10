
from building import *

cwd     = GetCurrentDir()
src     = ['aht10.c']
path    = [cwd]

if GetDepend('AHT10_USING_SENSOR_DEVICE'):
    src += ['sensor_asair_aht10.c']

group = DefineGroup('aht10', src, depend = ['PKG_USING_AHT10'], CPPPATH = path)

Return('group')
