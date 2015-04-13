姓名：劉亮谷
系級：資訊106
學號：F64011279

(a)
result:
0000000000600e50 d _DYNAMIC
0000000000600fe8 d _GLOBAL_OFFSET_TABLE_
0000000000400608 R _IO_stdin_used
				 w _Jv_RegisterClasses
00000000004004b4 T _Z7averagePdRd
00000000004004e2 T _Z7averageif
0000000000600e30 d __CTOR_END__
0000000000600e28 d __CTOR_LIST__
0000000000600e40 D __DTOR_END__
0000000000600e38 d __DTOR_LIST__
0000000000400738 r __FRAME_END__
0000000000600e48 d __JCR_END__
0000000000600e48 d __JCR_LIST__
0000000000601018 A __bss_start
0000000000601008 D __data_start
000004005c0 t __do_global_ctors_aux
0000000000400420 t __do_global_dtors_aux
0000000000601010 D __dso_handle
			     w __gmon_start__
0000000000600e24 d __init_array_end
0000000000600e24 d __init_array_start
00000000004005b0 T __libc_csu_fini
0000000000400520 T __libc_csu_init
                 U __libc_start_main@@GLIBC_2.2.5
0000000000601018 A _edata
0000000000601028 A _end
00000000004005f8 T _fini
0000000000400390 T _init
00000000004003d0 T _start
00000000004003fc t call_gmon_start
0000000000601018 b completed.6531
0000000000601008 W data_start
0000000000601020 b dtor_idx.6533
0000000000400490 t frame_dummy
000000000040050a T main

explaination:
00000000004004b4 T _Z7averagePdRd
00000000004004e2 T _Z7averageif
代表說compiler會以不同的命名來處理function overloading



(b)
output:
1 8
4 8
4 8
8 8

explaination:
pa, pb, pc, pd 皆為pointer，存的是 address, 所以都是8byte。
a, b, c, d 存的分別是 char, int, float, double，所以size是1, 4, 4, 8 byte。


