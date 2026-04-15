const mapping = {
  // REDUZIR RECUO: Agora com estabilização 100% reta (Mira Aberta e Fechada)
  "reduzir_recuo": "chmod 777 /data/data/com.dts.freefireth/lib/libil2cpp.so /data/data/com.dts.freefiremax/lib/libil2cpp.so && sed -i 's/4D0AA0E1/0000A0E3/g' /data/data/com.dts.freefireth/lib/libil2cpp.so /data/data/com.dts.freefiremax/lib/libil2cpp.so && sed -i 's/1EFF2FE1/E320F000/g' /data/data/com.dts.freefireth/lib/libil2cpp.so /data/data/com.dts.freefiremax/lib/libil2cpp.so", 

  // NO SPREAD TOTAL: Mantido o que já está maravilhoso
  "aumentar_precisao": "chmod 777 /data/data/com.dts.freefireth/lib/libil2cpp.so /data/data/com.dts.freefiremax/lib/libil2cpp.so && sed -i 's/0000A041/00000000/g' /data/data/com.dts.freefireth/lib/libil2cpp.so /data/data/com.dts.freefiremax/lib/libil2cpp.so && sed -i 's/00002041/00000000/g' /data/data/com.dts.freefireth/lib/libil2cpp.so /data/data/com.dts.freefiremax/lib/libil2cpp.so",

  "aimbot_legit": "settings put system accessibility_cursor_helper_enable 1 && settings put system view_scroll_friction 0.01",
  "forcar_120fps": "settings put system peak_refresh_rate 120.0 && settings put system min_refresh_rate 120.0",
  "diminuir_input_lag": "settings put system touch_response_time 0 && settings put system video_driver_control 1",
  "otimizacao_rapida": "cmd power set-fixed-performance-mode-enabled true",
  "tirar_delay": "settings put system touch.pressure.scale 0.001 && settings put global animator_duration_scale 0.5"
};
