# LEAP

L.E.A.P (飛躍) 是我的大學畢業專題(Graduation independent study)  
其全名為：輔助性動力輕型外骨骼(Lightweight Exoskeleton with Assistive Power)

# 說明

## MCU

我使用的微控制器型號為 STM32F103RB，是基於 ARM Cortex M3 的 32 位元微控制器。

本專案使用的 IDE 爲[ Atollic TrueSTUDIO](https://atollic.com/truestudio/)，這是 ST 官方維護、由開源的[ Eclipse ](https://www.eclipse.org/downloads/)發展而來的 IDE。

目前本專案可正常運作的專案在[ LEAP/LAEPK_STM32_Cpp ](https://github.com/ziteh/LEAP/tree/master/LAEPK_STM32_Cpp)，可以使用 TrueSTUDIO 直接開啓專案。

## 電腦端程式

電腦端程式可以查看外骨骼的相關數值與狀態，也可以控制其動作等。

# 系列

L.E.A.P 是由一系列不同的專案組合而成的，以下列出所有與 L.E.A.P 相關 repo：

* [LEAP-stm32: The STM32 MCU part](https://github.com/ziteh/LEAP-stm32)
* [LEAP-android-control-panel: The Android App part](https://github.com/ziteh/LEAP-android-control-panel)
