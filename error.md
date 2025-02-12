Run west build -s zmk/app -d "/tmp/tmp.tklGZwevfe" -b "nice_nano_v2" -- -DZMK_CONFIG=/\_\_w/zmk-urchin/zmk-urchin/config -DSHIELD="urchin_right nice_view_adapter nice_view_gem"

- west build -s zmk/app -d /tmp/tmp.tklGZwevfe -b nice_nano_v2 -- -DZMK_CONFIG=/**w/zmk-urchin/zmk-urchin/config -DSHIELD=urchin_right nice_view_adapter nice_view_gem
  -- west build: generating a build system
  Loading Zephyr default modules (Zephyr base).
  -- Application: /**w/zmk-urchin/zmk-urchin/zmk/app
  -- CMake version: 3.30.0
  -- Found Python3: /usr/bin/python3 (found suitable version "3.12.3", minimum required is "3.8") found components: Interpreter
  -- Cache files will be written to: /**w/zmk-urchin/zmk-urchin/zephyr/.cache
  -- Zephyr version: 3.5.0 (/**w/zmk-urchin/zmk-urchin/zephyr)
  -- Found west (found suitable version "1.2.0", minimum required is "0.14.0")
  -- Adding /**w/zmk-urchin/zmk-urchin/urchin-zmk-module/boards/shields/urchin
  -- Adding /**w/zmk-urchin/zmk-urchin/nice-view-gem/boards/shields/nice_view_gem
  -- Adding /**w/zmk-urchin/zmk-urchin/zmk/app/boards/shields/nice_view_adapter
  -- ZMK Config directory: /**w/zmk-urchin/zmk-urchin/config
  -- ZMK Config Kconfig: /**w/zmk-urchin/zmk-urchin/config/urchin.conf
  -- Using keymap file: /**w/zmk-urchin/zmk-urchin/config/urchin.keymap
  -- Using keymap file: /**w/zmk-urchin/zmk-urchin/config/urchin.keymap
  -- Board: nice_nano_v2
  -- Shield(s): urchin_right nice_view_adapter nice_view_gem
  -- ZEPHYR_TOOLCHAIN_VARIANT not set, trying to locate Zephyr SDK
  -- Found host-tools: zephyr 0.16.3 (/opt/zephyr-sdk-0.16.3)
  -- Found toolchain: zephyr 0.16.3 (/opt/zephyr-sdk-0.16.3)
  -- Found Dtc: /opt/zephyr-sdk-0.16.3/sysroots/x86_64-pokysdk-linux/usr/bin/dtc (found suitable version "1.6.0", minimum required is "1.4.6")
  -- Found BOARD.dts: /**w/zmk-urchin/zmk-urchin/zmk/app/boards/arm/nice_nano/nice_nano_v2.dts
  -- Found devicetree overlay: /**w/zmk-urchin/zmk-urchin/urchin-zmk-module/boards/shields/urchin/urchin_right.overlay
  -- Found devicetree overlay: /**w/zmk-urchin/zmk-urchin/zmk/app/boards/shields/nice_view_adapter/nice_view_adapter.overlay
  -- Found devicetree overlay: /**w/zmk-urchin/zmk-urchin/zmk/app/boards/shields/nice_view_adapter/boards/nice_nano_v2.overlay
  -- Found devicetree overlay: /**w/zmk-urchin/zmk-urchin/nice-view-gem/boards/shields/nice_view_gem/nice_view_gem.overlay
  -- Found devicetree overlay: /**w/zmk-urchin/zmk-urchin/config/urchin.keymap
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/behaviors/zmk,behavior-hold-tap.yaml for node /behaviors/quick_tap.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/behaviors/zmk,behavior-macro.yaml for node /macros/unstick.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/default_layer.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/sym_layer.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/ext_layer.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/fnc_layer.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/symbols_2_layer.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/accent_layer.
  'label' is marked as deprecated in 'properties:' in /**w/zmk-urchin/zmk-urchin/zmk/app/dts/bindings/zmk,keymap.yaml for node /keymap/settings_layer.
  -- Generated zephyr.dts: /tmp/tmp.tklGZwevfe/zephyr/zephyr.dts
  -- Generated devicetree_generated.h: /tmp/tmp.tklGZwevfe/zephyr/include/generated/devicetree_generated.h
  -- Including generated dts.cmake file: /tmp/tmp.tklGZwevfe/zephyr/dts.cmake

warning: ZMK_USB (defined at /\_\_w/zmk-urchin/zmk-urchin/zmk/app/Kconfig:121) was assigned the value
'y' but got the value 'n'. Check these unsatisfied dependencies: (!ZMK_SPLIT || (ZMK_SPLIT &&
ZMK_SPLIT_ROLE_CENTRAL)) (=n). See http://docs.zephyrproject.org/latest/kconfig.html#CONFIG_ZMK_USB
and/or look up ZMK_USB in the menuconfig/guiconfig interface. The Application Development Primer,
Setting Configuration Values, and Kconfig - Tips and Best Practices sections of the manual might be
helpful too.

warning: ZMK_WIDGET_BATTERY_STATUS_SHOW_PERCENTAGE (defined at /\_\_w/zmk-urchin/zmk-
urchin/zmk/app/src/display/widgets/Kconfig:18) was assigned the value 'y' but got the value 'n'.
Check these unsatisfied dependencies: ZMK_WIDGET_BATTERY_STATUS (=n). See
http://docs.zephyrproject.org/latest/kconfig.html#CONFIG_ZMK_WIDGET_BATTERY_STATUS_SHOW_PERCENTAGE
and/or look up ZMK_WIDGET_BATTERY_STATUS_SHOW_PERCENTAGE in the menuconfig/guiconfig interface. The
Application Development Primer, Setting Configuration Values, and Kconfig - Tips and Best Practices
sections of the manual might be helpful too.

warning: Deprecated symbol NRF_STORE_REBOOT_TYPE_GPREGRET is enabled.

Parsing /**w/zmk-urchin/zmk-urchin/zmk/app/Kconfig
warning: the value '2880 # default=960' is invalid for NICE_VIEW_GEM_ANIMATION_MS (defined at /**w/zmk-urchin/zmk-urchin/nice-view-gem/boards/shields/nice_view_gem/Kconfig.defconfig:42, /\_\_w/zmk-urchin/zmk-urchin/nice-view-gem/boards/shields/nice_view_gem/Kconfig.defconfig:42), which has type int -- assignment ignored

error: Aborting due to Kconfig warnings

Loaded configuration '/**w/zmk-urchin/zmk-urchin/zmk/app/boards/arm/nice_nano/nice_nano_v2_defconfig'
Merged configuration '/**w/zmk-urchin/zmk-urchin/zmk/app/prj.conf'
Merged configuration '/**w/zmk-urchin/zmk-urchin/config/urchin.conf'
Merged configuration '/**w/zmk-urchin/zmk-urchin/zmk/app/boards/shields/nice_view_adapter/nice_view_adapter.conf'
Merged configuration '/**w/zmk-urchin/zmk-urchin/nice-view-gem/boards/shields/nice_view_gem/nice_view_gem.conf'
CMake Error at /**w/zmk-urchin/zmk-urchin/zephyr/cmake/modules/kconfig.cmake:355 (message):
command failed with return code: 1
Call Stack (most recent call first):
/**w/zmk-urchin/zmk-urchin/zephyr/cmake/modules/zephyr_default.cmake:129 (include)
/**w/zmk-urchin/zmk-urchin/zephyr/share/zephyr-package/cmake/ZephyrConfig.cmake:66 (include)
/\_\_w/zmk-urchin/zmk-urchin/zephyr/share/zephyr-package/cmake/ZephyrConfig.cmake:92 (include_boilerplate)
CMakeLists.txt:9 (find_package)

-- Configuring incomplete, errors occurred!
FATAL ERROR: command exited with status 1: /usr/local/bin/cmake -DWEST_PYTHON=/usr/bin/python3 -B/tmp/tmp.tklGZwevfe -GNinja -DBOARD=nice_nano_v2 -DZMK_CONFIG=/**w/zmk-urchin/zmk-urchin/config '-DSHIELD=urchin_right nice_view_adapter nice_view_gem' -S/**w/zmk-urchin/zmk-urchin/zmk/app
Error: Process completed with exit code 1.
