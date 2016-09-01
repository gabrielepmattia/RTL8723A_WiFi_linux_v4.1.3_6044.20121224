===============================================================================
		Software Package - Component
===============================================================================
	1. ReleaseNotes.pdf

	2. document/
		2.1 Quick_Start_Guide_for_Driver_Compilation_and_Installation.pdf
		2.2 Quick_Start_Guide_for_Station_Mode.pdf
		2.3 wpa_cli_with_wpa_supplicant.pdf
		2.4 HowTo_support_more_VidPids.pdf
		2.5 Wireless_tools_porting_guide.pdf
		2.6 HowTo_enable_driver_to_support_WIFI_certification_test.pdf
		2.7 HowTo_enable_the_power_saving_functionality.pdf
		2.8 Quick_Start_Guide_for_SoftAP.pdf
		2.9 SoftAP_Mode_features.pdf
		2.10 linux_dhcp_server_notes.txt
		2.11 Quick_Start_Guide_for_Bridge.pdf
		2.12 RTL8192D_operation_mode.pdf
		2.13 RTK_Wi-Fi_Direct_Programming_guide.pdf
		2.14 Realtek_WiFi_concurrent_mode_Introduction.pdf	

	3. driver/
		3.1 rtl8723A_linux_v4.1.3_6044.20121224.tar.gz
			Naming rule: rtl[CHIPS]_linux_v[M].[N].[P]_[ssss].[yyyymmdd].tar.gz
			where:
				CHIPS: supported chips
				M: Major version
				N: miNor version
				P: Patch number
				s: SVN number
				y: package year
				m: package month
				d: package day

	4. wpa_supplicant_hostapd/
		4.1 wpa_supplicant_hostapd-0.8_rtw_20120803.zip
			4.1.1 wpa_supplicant
				The tool help the wlan network to communicate under the
				protection of WPAPSK mechanism (WPA/WPA2) and add WPS patch
			4.1.2 hostapd

		4.2 wpa_0_8.conf
			 Configure file sample for wpa_supplicant-0.8

		4.3 rtl_hostapd.conf
			 Configure files for Soft-AP mode

		4.4 p2p_hostapd.conf
			 Configure file for hostapd for Wi-Fi Direct (P2P)

	5. wireless_tools/
		5.1 wireless_tools.30.rtl.tar.gz

	6. WiFi_Direct_User_Interface/
		6.1 p2p_api_test_linux.c
		6.2 p2p_ui_test_linux.c
		6.3 p2p_test.h
		6.4 Start_Guide_P2P_User_Interface_Linux.pdf

	7. android_reference_codes/
		Suport Android 1.6 ~ 2.3 and use wireless extension(wext) interface.

		7.1 realtek_wifi_SDK_for_android_20120618.tar.gz
			This tar ball includes our android wifi reference codes

		7.2 realtek_wifi_SDK_for_android.txt
			Guide for porting Realtek wifi onto your Android system

	8. android_reference_codes_ICS_nl80211/
		Support Android 4.x (ICS) and use nl80211(cfg80211) interface.
		Driver should be configed to support nl80211(cfg80211).
		If have no idea how to config driver, please refer to following "User Guide for Driver Options".

		8.1 realtek_wifi_SDK_for_android_ICS_20120621.tar.gz
			This tar ball includes our android wifi reference codes for Android 4.x (ICS)

		8.2 Realtek_Wi-Fi_SDK_for_Android_ICS.pdf
			Guide for porting Realtek wifi onto your Android 4.x (ICS) system

	9. install.sh
		Script to compile and install WiFi driver easily in PC-Linux

==================================================================================================================
		User Guide for Driver compilation and installation
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_Driver_Compilation_and_Installation.pdf
==================================================================================================================
		User Guide for Station mode
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_Station_Mode.pdf
==================================================================================================================
		User Guide for Soft-AP mode
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_SoftAP.pdf
			(*) Please use wpa_supplicant_hostapd-0.8_rtw_20120803.zip
			(*) Please refer to document/linux_dhcp_server_notes.txt
==================================================================================================================
		User Guide for Wi-Fi Direct
==================================================================================================================
			(*) Please refer to document/RTK_Wi-Fi_Direct_Programming_guide.pdf
			(*) Please wpa_supplicant_hostapd-0.8_rtw_20120803.zip
			(*) Please refer to document/linux_dhcp_server_notes.txt
			(*) Please refer to sample_code/WiFi_Direct_User_Interface/
==================================================================================================================
		User Guide for WPS2.0
==================================================================================================================
			(*) Please use wpa_supplicant_hostapd-0.8_rtw_20120803.zip
==================================================================================================================
		User Guide for Driver Options
==================================================================================================================
			(*) Please refer to document/RTK_WLAN_Driver_Option_Setting_Guide.pdf
==================================================================================================================
		User Guide for Applying Wi-Fi solution onto Andriod System
==================================================================================================================
			(*) For Android 1.6 ~ 2.3, Please refer to android_reference_codes/realtek_wifi_SDK_for_android.txt
			(*) For Android 4.x (ICS), please refer to android_reference_codes_ICS_nl80211/Realtek_Wi-Fi_SDK_for_Android_ICS.pdf
