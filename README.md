# proprietary_vendor_samsung_gtaxlwifi
Private firmware dump for Samsung Galaxy Tab A 10.1 2016 Wi‑Fi (SM‑T580 / gtaxlwifi).


Contents were pulled from an Android device:
- `/vendor/firmware/*`
- `/vendor/firmware/wlan/*`
- `/vendor/etc/wifi/*` (optional configs)

## Intended use

Use as a source for local postmarketOS packaging (e.g. firmware-samsung-gtaxlwifi).

## Notes

Wi‑Fi chipset observed: QCA9377 (SDIO)

Relevant WLAN config files:
- `vendor_firmware/wlan/WCNSS_cfg.dat`
- `vendor_firmware/wlan/qcom_cfg.ini`
- `vendor_firmware/wlan/grippower.info`
