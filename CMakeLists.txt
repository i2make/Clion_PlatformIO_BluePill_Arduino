# !!! WARNING !!! AUTO-GENERATED FILE, PLEASE DO NOT MODIFY IT AND USE
# https://docs.platformio.org/page/projectconf/section_env_build.html#build-flags
#
# If you need to override existing CMake configuration or add extra,
# please create `CMakeListsUser.txt` in the root of project.
# The `CMakeListsUser.txt` will not be overwritten by PlatformIO.

cmake_minimum_required(VERSION 3.13)
set(CMAKE_SYSTEM_NAME Generic)
set(CMAKE_C_COMPILER_WORKS 1)
set(CMAKE_CXX_COMPILER_WORKS 1)

project("bluepill_arduino" C CXX)

#=====================================================================
#
# !!! WARNING !!! AUTO-GENERATED FILE, PLEASE DO NOT MODIFY IT AND USE
# https://docs.platformio.org/page/projectconf/section_env_build.html#build-flags
#
# If you need to override existing CMake configuration or add extra,
# please create `CMakeListsUser.txt` in the root of project.
# The `CMakeListsUser.txt` will not be overwritten by PlatformIO.
#
#=====================================================================

set(CMAKE_CONFIGURATION_TYPES "bluepill_f103c8" CACHE STRING "Build Types reflect PlatformIO Environments" FORCE)

set(CLION_SVD_FILE_PATH "$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/platforms/ststm32/misc/svd/STM32F103xx.svd" CACHE FILEPATH "Peripheral Registers Definitions File" FORCE)

SET(CMAKE_C_COMPILER "$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/bin/arm-none-eabi-gcc.exe")
SET(CMAKE_CXX_COMPILER "$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/bin/arm-none-eabi-g++.exe")
SET(CMAKE_CXX_FLAGS "-std=gnu++14 -fno-threadsafe-statics -fno-rtti -fno-exceptions -fno-use-cxa-atexit -Os -mcpu=cortex-m3 -mthumb -ffunction-sections -fdata-sections -Wall -nostdlib --param max-inline-insns-single=500")

SET(CMAKE_C_FLAGS "-std=gnu11 -Os -mcpu=cortex-m3 -mthumb -ffunction-sections -fdata-sections -Wall -nostdlib --param max-inline-insns-single=500")

SET(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 14)

if (CMAKE_BUILD_TYPE MATCHES "bluepill_f103c8")
    add_definitions(-D'PLATFORMIO=50001')
    add_definitions(-D'STM32F103xB') # STM32F103x6 or STM32F103x8 or STM32F103xB
    add_definitions(-D'STM32F1xx')
    add_definitions(-D'ARDUINO=10808')
    add_definitions(-D'ARDUINO_ARCH_STM32')
    add_definitions(-D'ARDUINO_BLUEPILL_F103C8')
    add_definitions(-D'BOARD_NAME=\"BLUEPILL_F103C8\"')
    add_definitions(-D'HAL_UART_MODULE_ENABLED')

    include_directories("${CMAKE_CURRENT_LIST_DIR}/include")
    include_directories("${CMAKE_CURRENT_LIST_DIR}/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/avr")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/stm32")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/stm32/LL")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/stm32/usb")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/stm32/OpenAMP")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/stm32/usb/hid")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino/stm32/usb/cdc")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Drivers/STM32F4xx_HAL_Driver/Inc")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Drivers/STM32F4xx_HAL_Driver/Src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/STM32F1xx")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Middlewares/ST/STM32_USB_Device_Library/Core/Inc")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Middlewares/ST/STM32_USB_Device_Library/Core/Src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Middlewares/OpenAMP")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Middlewares/OpenAMP/open-amp/lib/include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Middlewares/OpenAMP/libmetal/lib/include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Middlewares/OpenAMP/virtual_driver")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-cmsis/CMSIS/Core/Include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Drivers/CMSIS/Device/ST/STM32F1xx/Include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/system/Drivers/CMSIS/Device/ST/STM32F1xx/Source/Templates/gcc")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-cmsis/CMSIS/DSP/Include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/cores/arduino")

    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/variants/Generic_F103Cx")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/CMSIS_DSP/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/EEPROM/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/IWatchdog/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/Keyboard/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/Mouse/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/SPI/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/Servo/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/SoftwareSerial/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/SrcWrapper/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/framework-arduinoststm32/libraries/Wire/src")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/arm-none-eabi/include/c++/9.2.1")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/arm-none-eabi/include/c++/9.2.1/arm-none-eabi")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/lib/gcc/arm-none-eabi/9.2.1/include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/lib/gcc/arm-none-eabi/9.2.1/include-fixed")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/toolchain-gccarmnoneeabi/arm-none-eabi/include")
    include_directories("$ENV{HOMEDRIVE}$ENV{HOMEPATH}/.platformio/packages/tool-unity")

    FILE(GLOB_RECURSE EXTRA_LIB_SOURCES
            ${CMAKE_CURRENT_LIST_DIR}/.pio/libdeps/bluepill_f103c8/*.*
            )
endif()


FILE(GLOB_RECURSE SRC_LIST
        ${CMAKE_CURRENT_LIST_DIR}/src/*.*
        ${CMAKE_CURRENT_LIST_DIR}/lib/*.*
        )

list(APPEND SRC_LIST ${EXTRA_LIB_SOURCES})


#====================================================================


if(EXISTS ${CMAKE_CURRENT_SOURCE_DIR}/CMakeListsUser.txt)
    include(CMakeListsUser.txt)
endif()

#===========================================================
#           Target
#===========================================================
add_custom_target(
        Production ALL
        COMMAND platformio -c clion run "$<$<NOT:$<CONFIG:All>>:-e${CMAKE_BUILD_TYPE}>"
        WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}
)

add_custom_target(
        Debug ALL
        COMMAND platformio -c clion run --target debug "$<$<NOT:$<CONFIG:All>>:-e${CMAKE_BUILD_TYPE}>"
        WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}
)

add_executable(Z_DUMMY_TARGET ${SRC_LIST})
