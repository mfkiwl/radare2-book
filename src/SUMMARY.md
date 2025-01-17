# Summary

* [Introduction](README.md)
   * [History](first_steps/history.md)
   * [The Framework](first_steps/overview.md)
   * [Downloading radare2](first_steps/getting_radare.md)
   * [Compilation and Portability](first_steps/compilation_portability.md)
   * [Compilation on Windows](first_steps/windows_compilation.md)
   * [Compilation on Android](first_steps/compilation_android.md)
   * [User Interfaces](first_steps/ui.md)
* [First Steps](first_steps/intro.md)
   * [Command-line Flags](first_steps/commandline_flags.md)
   * [Command Format](first_steps/command_format.md)
   * [Expressions](first_steps/expressions.md)
   * [Basic Debugger Session](first_steps/basic_debugger_session.md)
   * [Contributing to radare2](first_steps/contributing.md)
* [Configuration](configuration/intro.md)
   * [Colors](configuration/colors.md)
   * [Configuration Variables](configuration/evars.md)
   * [Files](configuration/files.md)
* [Basic Commands](basic_commands/intro.md)
   * [Seeking](basic_commands/seeking.md)
   * [Block Size](basic_commands/block_size.md)
   * [Sections](basic_commands/sections.md)
   * [Mapping Files](basic_commands/mapping_files.md)
   * [Print Modes](basic_commands/print_modes.md)
   * [Flags](basic_commands/flags.md)
   * [Write](basic_commands/write.md)
   * [Zoom](basic_commands/zoom.md)
   * [Yank/Paste](basic_commands/yank_paste.md)
   * [Comparing Bytes](basic_commands/comparing_bytes.md)
      * [Watching for Changes](basic_commands/cmp_watchers.md)
   * [SDB](basic_commands/sdb.md)
   * [Dietline](basic_commands/dietline.md)
* [Visual mode](visual_mode/intro.md)
   * [Visual Disassembly](visual_mode/visual_disassembly.md)
   * [Visual Assembler](visual_mode/visual_assembler.md)
   * [Visual Configuration Editor](visual_mode/visual_configuration_editor.md)
   * [Visual Panels](visual_mode/visual_panels.md)
* [Searching bytes](search_bytes/intro.md)
   * [Basic Searches](search_bytes/basic_searches.md)
   * [Configurating the Search](search_bytes/configurating_the_search.md)
   * [Pattern Search](search_bytes/pattern_search.md)
   * [Automation](search_bytes/automation.md)
   * [Backward Search](search_bytes/backward_search.md)
   * [Search in Assembly](search_bytes/search_in_assembly.md)
   * [Searching for Cryptography materials](search_bytes/searching_crypto.md)
* [Disassembling](disassembling/intro.md)
   * [Adding Metadata](disassembling/adding_metadata.md)
   * [ESIL](disassembling/esil.md)
* [Analysis](analysis/intro.md)
   * [Code Analysis](analysis/code_analysis.md)
   * [Variables](analysis/variables.md)
   * [Types](analysis/types.md)
   * [Calling Conventions](analysis/calling_conventions.md)
   * [Virtual Tables](analysis/vtables.md)
   * [Syscalls](analysis/syscalls.md)
   * [Emulation](analysis/emulation.md)
   * [Symbols information](analysis/symbols.md)
   * [Signatures](signatures/zignatures.md)
   * [Graph commands](analysis/graphs.md)
* [Scripting](scripting/intro.md)
   * [Loops](scripting/loops.md)
   * [Macros](scripting/macros.md)
   * [R2pipe](scripting/r2pipe.md)
* [Debugger](debugger/intro.md)
   * [Getting Started](debugger/getting_started.md)
   * [Migration from ida, GDB or WinDBG](debugger/migration.md)
   * [Registers](debugger/registers.md)
   * [Memory Maps](debugger/memory_maps.md)
   * [Heap](debugger/heap.md)
   * [Files](debugger/files.md)
   * [Reverse Debugging](debugger/revdebug.md)
   * [Windows Messages](debugger/windows_messages.md)
* [Remote Access](debugger/remoting_capabilities.md)
   * [Remote GDB](debugger/remote_gdb.md)
   * [Remote WinDbg](debugger/windbg.md)
* [Command Line Tools](tools/intro.md)
   * [Rax2](tools/rax2/intro.md)
   * [Rafind2](tools/rafind2/intro.md)
   * [Rarun2](tools/rarun2/intro.md)
   * [Rabin2](tools/rabin2/intro.md)
      * [File Identification](tools/rabin2/file_identification.md)
      * [Entrypoint](tools/rabin2/entrypoints.md)
      * [Imports](tools/rabin2/imports.md)
      * [Exports](tools/rabin2/exports.md)
      * [Symbols](tools/rabin2/symbols.md)
      * [Libraries](tools/rabin2/libraries.md)
      * [Strings](tools/rabin2/strings.md)
      * [Program Sections](tools/rabin2/program_sections.md)
   * [Radiff2](tools/radiff2/intro.md)
      * [Binary Diffing](tools/radiff2/binary_diffing.md)
   * [Rasm2](tools/rasm2/intro.md)
      * [Assemble](tools/rasm2/assemble.md)
      * [Disassemble](tools/rasm2/disassemble.md)
      * [Configuration](tools/rasm2/config.md)
   * [Ragg2](tools/ragg2/ragg2.md)
      * [Language](tools/ragg2/lang.md)
   * [Rahash2](tools/rahash2/intro.md)
      * [Rahash Tool](tools/rahash2/rahash_tool.md)
* [Plugins](plugins/intro.md)
   * [IO plugins](plugins/ioplugins.md)
   * [Asm plugins](plugins/dev-asm.md)
   * [Analysis plugins](plugins/dev-anal.md)
   * [Bin plugins](plugins/dev-bin.md)
   * [Other plugins](plugins/dev-other.md)
   * [Python plugins](plugins/python.md)
   * [Debugging](plugins/debug.md)
   * [Testing](plugins/testing.md)
   * [Packaging](plugins/r2pm.md)
* [Crackmes](crackmes/intro.md)
   * [IOLI](crackmes/ioli/intro.md)
       * [IOLI 0x00](crackmes/ioli/ioli_0x00.md)
       * [IOLI 0x01](crackmes/ioli/ioli_0x01.md)
       * [IOLI 0x02](crackmes/ioli/ioli_0x02.md)
       * [IOLI 0x03](crackmes/ioli/ioli_0x03.md)
       * [IOLI 0x04](crackmes/ioli/ioli_0x04.md)
       * [IOLI 0x05](crackmes/ioli/ioli_0x05.md)
       * [IOLI 0x06](crackmes/ioli/ioli_0x06.md)
       * [IOLI 0x07](crackmes/ioli/ioli_0x07.md)
       * [IOLI 0x08](crackmes/ioli/ioli_0x08.md)
       * [IOLI 0x09](crackmes/ioli/ioli_0x09.md)
   * [Avatao R3v3rs3 4](crackmes/avatao/01-reverse4/intro.md)
       * [.radare2](crackmes/avatao/01-reverse4/radare2.md)
       * [.first_steps](crackmes/avatao/01-reverse4/first_steps.md)
       * [.main](crackmes/avatao/01-reverse4/main.md)
       * [.vmloop](crackmes/avatao/01-reverse4/vmloop.md)
       * [.instructionset](crackmes/avatao/01-reverse4/instructionset.md)
       * [.bytecode](crackmes/avatao/01-reverse4/bytecode.md)
       * [.outro](crackmes/avatao/01-reverse4/outro.md)
* [Reference Card](refcard/intro.md)
* [Acknowledgments](credits/credits.md)
