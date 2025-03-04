from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f413_acc.c'),
os.path.join(src_path, 'at32f413_adc.c'),
os.path.join(src_path, 'at32f413_bpr.c'),
os.path.join(src_path, 'at32f413_can.c'),
os.path.join(src_path, 'at32f413_crc.c'),
os.path.join(src_path, 'at32f413_crm.c'),
os.path.join(src_path, 'at32f413_debug.c'),
os.path.join(src_path, 'at32f413_dma.c'),
os.path.join(src_path, 'at32f413_exint.c'),
os.path.join(src_path, 'at32f413_flash.c'),
os.path.join(src_path, 'at32f413_gpio.c'),
os.path.join(src_path, 'at32f413_i2c.c'),
os.path.join(src_path, 'at32f413_misc.c'),
os.path.join(src_path, 'at32f413_pwc.c'),
os.path.join(src_path, 'at32f413_rtc.c'),
os.path.join(src_path, 'at32f413_sdio.c'),
os.path.join(src_path, 'at32f413_spi.c'),
os.path.join(src_path, 'at32f413_tmr.c'),
os.path.join(src_path, 'at32f413_usart.c'),
os.path.join(src_path, 'at32f413_usb.c'),
os.path.join(src_path, 'at32f413_wdt.c'),
os.path.join(src_path, 'at32f413_wwdt.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F413_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
