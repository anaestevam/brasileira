# brasileira

cd src
alex ./lexer.x 
ghci ./parser.hs ./lexer.hs ./tokens.hs ./statements.hs ./memory.hs ./interpreter.hs  ./values.hs

main
main' "problema1.bra"
main' "problema2.bra"