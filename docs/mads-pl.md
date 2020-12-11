# [Mad-Assembler](https://github.com/tebe6502/Mad-Assembler)

**Mad-Assembler** (MADS) jest aplikacją 32 bitową, napisaną w **Delphi**. Większość asemblerów napisano w **C**, więc żeby się nie powtarzać użyłem **Delphi 7.0** ;)

W założeniu **MADS** skierowany jest do użytkowników **QA**, **XASM**, **FA**. Z **QA** zapożyczona została składnia, z **XASM** niektóre makro rozkazy i zmiany składni, z **FA** obsługa składni **Sparta DOS X** **SDX**. Umożliwione zostało użycie dodatkowych znaków w nazwach etykiet. Poza tym dodana została obsługa **CPU 65816**, makr, procedur, podziału pamięci na wirtualne banki, wielowymiarowych nazw etykiet.

Maksymalna liczba etykiet i makr ograniczona jest ilością pamięci komputera *PC*. Konkretnie można dokonać **2147483647** `INTEGER` wpisów do tablic dynamicznych. Jestem pewien że taka ilość jest wystarczająca :)

Operacje arytmetyczne dokonywane są na wartościach typu `INT64` (signed 64 bit), wynik reprezentowany jest na wartościach typu `CARDINAL` (unsigned 32 bit).
Jeden wiersz może mieć długość **65535** bajtów, takiej długości może być też nazwa etykiety. Nie miałem jednak okazji sprawdzić tak długich etykiet i wierszy :)

Dzięki darmowemu kompilatorowi **Free Pascal Compiler** (FPC) możliwa jest kompilacja **MADS** dla innych platform systemowych, np. **Linux**, **Mac**, **OS/2** itp.

## [Wydanie](https://github.com/tebe6502/Mad-Assembler/releases)

Pod powyższym *linkiem* znajdziesz kompilacje **Mad-Assembler** dla systemu **Windows**.

## [Dokumentacja](https://tebe6502.github.io/mad-assembler-mkdocs/)

Pod powyższym *linkiem* znajdziesz najnowszą wersję dokumentacji.
