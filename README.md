<div align="center">
    <h1>🔥BurntPunX</h1>
</div>
<br>
<div align="center">
    <a href="https://twitter.com/HoodieCartel">HoodieCartel</a> | <a href="https://twitter.com/UniversalPunX">UniversalPunX</a>
</div>
 <br>
<div align="center">
    Thank you to the PunX who contributed to this repo:
</div>
<br>
<div align="center">
    <a href="https://twitter.com/mrmaiko">mrmaiko</a> | <a href="https://twitter.com/FyzzNFT">FyzzNFT</a> | <a href="https://twitter.com/Official_Chonii">Official_Chonii</a> | <a href="https://twitter.com/aurealarcon">aurealarcon</a> | <a href="https://twitter.com/b00ste_lyx">b00ste_lyx</a> | <a href="https://twitter.com/tantodefi">tantodefi</a> | <a href="https://twitter.com/ChudBrass">ChudBrass</a> | <a href="https://twitter.com/zeroxLucky">zeroxLucky</a>
</div>
<br>




               ....                                                             .....
               :+##=                                                            -*#*:
               :*##+:                                                          :+##*:
               :*###=.                                                        .=*##*:
               :***#+-----:                                              .-----+*##*:
               :*********#*                .....::::.:..:.               +**********:
               .-===+******:::..        ...:....:::-:-:::-::        ..:::+******+==-.
                   .+********#**+    ..::::::::::::::::::-:::::    =++*********+:
                   .:===*****#*#+. ....:....::::::::::::::::::::. .=++******+==:.
                       -*****#***-:...:::::::::::::::::::::::-...::=++******-
                       .=+==+++**..   .:::::::::::::::::::::::   ..+*+**+++=:
                           :=++++..   .::::::::::::::::::::::-   ::+***+:
                           :-----...  .::::::::::::::::::::::-...::-----:
                                 ......::::::::::::::::::::::-:::::
                                 ......::::::::::::::::::::::-:::::
                                 ..:...::::::::::::::::::::::-:::--
                                =::::::::::::::::::::::::::::-::--=+
                            -++...                           .  ...::++-
                           :###.                                    -@%%:
                        -###+++-------------------------------------=***%%%=
                     -=+#***:::-***********************************#----###%+=-
                    +#%*====. ..------------------------------------.  .====#%%+
                 ::+%##*-:::.                                          .:::-#%%%*::
                =%##%%%#:         ....                        .....        :*%%%%%%=
               =%#######:        ::::::......................::::::        :+###%%%%-
              -#%#######:        ............................:..:::       ..=####%%%#.
              +%########:....    ............................:.....    .....=#######%=
              -****#####-.::. .. ............................:.....    ....:=####***#=
              =*******##-:::. .. ............................:..... .. .::.:=*******#+
              =#***#####----.... ............................:..... .......:=#####**#=
              -****++++#***+...........:........................... ....-++***+++***#=
              -#**+====####*.... .................................  ....-####+===+#*#-
              -***+===+##*#*....  .........:.................. ..   ....-*#*#*++=+**#-
              :****===*####*::::...........:........................::::=*####++++**#:
              :****===+***####*:...............:::::::........ .....:+*++*****+++*#*#:
              :****++++*#######-:::............:.....:........ ..:::-+*++*###***+*###:
               ---+********+++*#**#.   .......::::::::.......   .****++==+***###*+==-
                  =****+-=====+####-...........::....:.........:-****+===---=***#=
                  =#*******=--=+++*###*..................   .*##**+++=--=++==*###=
                  .:::=***#+--====+#**#. ................   .***#*=+=---=****+:::.
                      :***#++++---=****. ................   .+***=--=+===***#:
                      .***##***-::-****. ................   .****=--=***+****.
                       ...:****=--=***#...................  .****+===****:...
                           :-:-++++****:.....................+*******---:
                               --=+==+*+++===================+++**+==.
                       :--------:===+******************************+********+
                       =+++++++==+***************************************####.
                      .+++++++++==*##****####****####****###*****#**********#=           




                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        









This  is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

###        Getting Started 1

First,  run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## GRID and up-provider

Now you can use the UP Provider anywhere in your app by importing the useUP hook:
```
import { useUP } from '@/components/contexts/UPContext';

function YourComponent() {
  const { walletConnected, accounts, connect, disconnect } = useUP();

  useEffect(() => {
    console.log('Wallet state:', { walletConnected, accounts });
  }, [walletConnected, accounts]);

  return (
    <div>
      {walletConnected ? (
        <>
          <div>Connected: {accounts[0]}</div>
          <button onClick={disconnect}>Disconnect</button>
        </>
      ) : (
        <button onClick={connect}>Connect UP</button>
      )}
    </div>
  );
}
```
