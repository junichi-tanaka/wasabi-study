
QEMU := /opt/homebrew/Cellar/qemu/10.0.0/bin/qemu-system-x86_64

img.bin:
	xxd -r -p img.hex > img.bin

qemu: img.bin
	$(QEMU) -drive file=img.bin,format=raw

