zephyr_sources_ifdef(CONFIG_DMA_QMSI		dma_qmsi.c)
zephyr_sources_ifdef(CONFIG_DMA_SAM_XDMAC	dma_sam_xdmac.c)
zephyr_sources_ifdef(CONFIG_DMA_STM32F4X	dma_stm32f4x.c)

zephyr_sources_ifdef(CONFIG_USERSPACE		dma_handlers.c)
