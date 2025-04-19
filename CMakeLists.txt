add_executable(radar_qt
    main.cpp

    src/controller/AppController.cpp
    src/controller/ShortcutHandler.cpp

    src/model/SdrDevice.cpp
    src/model/CaptureWorker.cpp
    src/model/DspWorker.cpp
    src/model/RingBuffer.cpp

    src/view/MainWindow.cpp
    src/view/ControlPanel.cpp
    src/view/WaterfallWidget.cpp
)
