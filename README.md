## UNMAINTAINED

forked by mengwong to fix some bugs induced by Haskell upgrading

    language-typescript> configure (lib)
    language-typescript> Configuring language-typescript-0.0.4...
    language-typescript> build (lib)
    language-typescript> Preprocessing library for language-typescript-0.0.4..
    language-typescript> Building library for language-typescript-0.0.4..
    language-typescript> [1 of 5] Compiling Language.TypeScript.Lexer
    language-typescript>
    language-typescript> /Users/mengwong/src/language-typescript/src/Language/TypeScript/Lexer.hs:51:16: warning: [-Wtabs]
    language-typescript>     Tab character found here.
    language-typescript>     Please use spaces instead.
    language-typescript>    |
    language-typescript> 51 | typeScriptDef = javaStyle
    language-typescript>    |                ^
    language-typescript> [2 of 5] Compiling Language.TypeScript.Types
    language-typescript>
    language-typescript> /Users/mengwong/src/language-typescript/src/Language/TypeScript/Types.hs:28:10: error:
    language-typescript>     • No instance for (Semigroup Comment)
    language-typescript>         arising from the superclasses of an instance declaration
    language-typescript>     • In the instance declaration for ‘Monoid Comment’
    language-typescript>    |
    language-typescript> 28 | instance Monoid Comment where
    language-typescript>    |          ^^^^^^^^^^^^^^
    language-typescript>

    --  While building package language-typescript-0.0.4 using:
          /Users/mengwong/.stack/setup-exe-cache/x86_64-osx/Cabal-simple_mPHDZzAJ_2.4.0.1_ghc-8.6.5 --builddir=.stack-work/dist/x86_64-osx/Cabal-2.4.0.1 build lib:language-typescript --ghc-options " -fdiagnostics-color=always"
        Process exited with code: ExitFailure 1
    Progress 1/2

### language-typescript

Haskell library for working with TypeScript Definition files
