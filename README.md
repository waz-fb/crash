03-15 17:33:18.945 21695 21743 E AndroidRuntime: FATAL EXCEPTION: UnityMain
03-15 17:33:18.945 21695 21743 E AndroidRuntime: Process: com.beatgames.beatsaber, PID: 21695
03-15 17:33:18.945 21695 21743 E AndroidRuntime: java.lang.Error: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-15 17:33:18.945 21695 21743 E AndroidRuntime: Version '2019.3.15f1 (59ff3e03856d)', Build type 'Release', Scripting Backend 'il2cpp', CPU 'arm64-v8a'
03-15 17:33:18.945 21695 21743 E AndroidRuntime: Build fingerprint: 'oculus/hollywood/hollywood:10/QQ3A.200605.001/12835800058000000:user/release-keys'
03-15 17:33:18.945 21695 21743 E AndroidRuntime: Revision: '0'
03-15 17:33:18.945 21695 21743 E AndroidRuntime: ABI: 'arm64'
03-15 17:33:18.945 21695 21743 E AndroidRuntime: Timestamp: 2021-03-15 17:33:18-0700
03-15 17:33:18.945 21695 21743 E AndroidRuntime: pid: 21695, tid: 21743, name: UnityMain  >>> com.beatgames.beatsaber <<<
03-15 17:33:18.945 21695 21743 E AndroidRuntime: uid: 10082
03-15 17:33:18.945 21695 21743 E AndroidRuntime: signal 6 (SIGABRT), code -1 (SI_QUEUE), fault addr --------
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x0  0000000000000000  x1  00000000000054ef  x2  0000000000000006  x3  00000076d64448c0
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x4  fefeff74ff666d68  x5  fefeff74ff666d68  x6  fefeff74ff666d68  x7  7f7f7f7f7f7f7f7f
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x8  00000000000000f0  x9  fbd90ab02beabe6b  x10 0000000000000001  x11 0000000000000000
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x12 fffffff0fffffbdf  x13 00000000604ffcce  x14 002963afdee874aa  x15 000018e7876a81dd
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x16 00000077c4bc23f8  x17 00000077c4ba24c0  x18 00000076d94ad000  x19 00000000000054bf
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x20 00000000000054ef  x21 00000000ffffffff  x22 ffffff80ffffffc8  x23 00000076d6444b10
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x24 00000076d64449f0  x25 00000076d6444a30  x26 00000076db12ece8  x27 00000076d64450a0
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     x28 00000076db12ec00  x29 00000076d6444940
03-15 17:33:18.945 21695 21743 E AndroidRuntime:     sp  00000076d64448a0  lr  00000077c4b5518c  pc  00000077c4b551b8
03-15 17:33:18.945 21695 21743 E AndroidRuntime: 
03-15 17:33:18.945 21695 21743 E AndroidRuntime: backtrace:
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #00 pc 00000000000801b8  /apex/com.android.runtime/lib64/bionic/libc.so (prop_area::foreach_property(prop_bt*, void (*)(prop_info const*, void*), void*)+132) (BuildId: d103c38b4b0eaa366a982b6fbf424e5e)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #01 pc 00000000000db698  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (std::set_unexpected(void (*)())) (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #02 pc 00000000000db718  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #03 pc 00000000000d86e0  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #04 pc 00000000000d8688  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (std::terminate()+52) (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #05 pc 0000000000071d20  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (void LoggerContextObject::critical<char const*, char const*, int>(std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, char const*, char const*, int) const) (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #06 pc 000000000007077c  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (il2cpp_functions::Init()+11964) (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #07 pc 0000000000086e88  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (il2cpp_utils::GetClassFromName(std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >)+48) (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #08 pc 0000000000068d0c  /data/data/com.beatgames.beatsaber/libbeatsaber-hook_1_0_12.so (il2cpp_utils::FindMethodUnsafe(std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, int)+28) (BuildId: 05be2777ad8c162af5279036f5b2ebd2952446a4)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #09 pc 000000000001f994  /data/data/com.beatgames.beatsaber/libgoodbyebug.so (load+72) (BuildId: f60de533924b18de9fd959244521fa2b78136b2d)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #10 pc 0000000000044bbc  /data/app/com.beatgames.beatsaber-KrCJthuPWGyz2GFyKtO34Q==/lib/arm64/libmodloader.so (Mod::load_mod()+128) (BuildId: 07fa01771e5e50ba8448f10f8d80d8f2dabd1b56)
03-15 17:33:18.945 21695 21743 E AndroidRuntime:       #11 pc 00000000000447b8  /data/app/com.beatgames.beatsaber-KrCJthuPWGyz2GFyKtO34Q==/lib/arm64/libmodloader.so (Modloader::load_mods()+184) (BuildId: 07fa01771e5e50ba8448f10f8d80d8f2dabd1b56)
03-15 17:33:18.946 21695 21743 E AndroidRuntime:       #12 pc 00000000005d0508  /data/app/com.beatgames.beatsaber-KrCJthuPWGyz2GFyKtO34Q==/lib/arm64/libunity.so (BuildId: fb3c121a1811d470c9d17ee368cd7227475dc348)
03-15 17:33:18.946 21695 21743 E AndroidRuntime:       #13 pc 0000000000639d5c  /data/app/com.beatgames.beatsaber-KrCJthuPWGyz2GFyKtO34Q==/lib/arm64/libunity.so (BuildId: fb3c121a1811d470c9d17ee368cd7227475dc348)
03-15 17:33:18.946 21695 21743 E AndroidRuntime:       #14 pc 000000000063a80c  /data/app/com.beatgames.beatsaber-KrCJthuPWGyz2GFyKtO34Q==/lib/arm64/libunity.so (BuildId: fb3c121a1811d470c9d17ee368cd7227475dc348)
03-15 17:33:18.946 21695 21743 E AndroidRuntime:       #15 pc 000000000064e648  /data/app/com.beatgames.beatsaber-KrCJthuPWGyz2GFyKtO34Q==/lib/arm64/libunity.so (BuildId: fb3c121a1811d470c9d17ee368cd7227475dc348)
03-15 17:33:18.946 21695 21743 E AndroidRuntime:       #16 pc 0000000000142750  /apex/com.android.runtime/lib64/libart.so (art_quick_alloc_array_resolved_region_tlab+112) (BuildId: 29ea7fcb82fbe4620fff88dcbd9f6777)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libc.prop_area::foreach_property(prop_bt*, void (*)(prop_info const*, void*), void*)(foreach_property:132)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.std::set_unexpected(void (*)())(set_unexpected:0)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.0xdb718(Native Method)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.0xd86e0(Native Method)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.std::terminate()(terminate:52)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.void LoggerContextObject::critical<char const*, char const*, int>(std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, char const*, char const*, int) const(critical<char const*, char const*, int>:0)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.il2cpp_functions::Init()(Init:11964)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.il2cpp_utils::GetClassFromName(std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >)(GetClassFromName:48)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libbeatsaber-hook_1_0_12.il2cpp_utils::FindMethodUnsafe(std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, std::__ndk1::basic_string_view<char, std::__ndk1::char_traits<char> >, int)(FindMethodUnsafe:28)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libgoodbyebug.load(load:72)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libmodloader.Mod::load_mod()(load_mod:128)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libmodloader.Modloader::load_mods()(load_mods:184)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libunity.0x5d0508(Native Method)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libunity.0x639d5c(Native Method)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libunity.0x63a80c(Native Method)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libunity.0x64e648(Native Method)
03-15 17:33:18.946 21695 21743 E AndroidRuntime: 	at libart.art_quick_alloc_array_resolved_region_tlab(art_quick_alloc_array_resolved_region_tlab:112)
