all:
	$(MAKE) -C ../vendor/libfx2/firmware/library all
	$(MAKE) -C ../firmware all
	cp ../firmware/glasgow.ihex glasgow/firmware.ihex

clean:
	$(MAKE) -C ../vendor/libfx2/firmware/library clean
	$(MAKE) -C ../firmware clean
	rm glasgow/firmware.ihex

.PHONY: all clean
