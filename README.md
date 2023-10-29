PS D:\myproject\blockchainrisein> npm run test<br/>

> bsc-starter-box@1.0.0 test<br/>
> truffle test<br/>

Using network 'development'.<br/>


Compiling your contracts...<br/>
===========================<br/>
> Compiling .\contracts\bsc\CarRentalPlatform.sol<br/>
> Compiling .\node_modules\@openzeppelin\contracts\security\ReentrancyGuard.sol<br/>
> Compiling .\node_modules\@openzeppelin\contracts\utils\Counters.sol<br/>
> Artifacts written to C:\Users\shash\AppData\Local\Temp\test--11900-s5OliT3jGTwK<br/>
> Compiled successfully using:<br/>
   - solc: 0.8.12+commit.f00d7308.Emscripten.clang<br/>
carRentalPlatformAddress = 0x0c15e0812f99306B2D5416bec3FA3E5b165aD25b<br/>


  Contract: CarRentalPlatform<br/>
    Add user and car<br/>
      ✔ adds a new user (867ms)<br/>
      ✔ adds a car (1251ms)<br/>
    Check out and check in car<br/>
      ✔ Check out a car (2846ms)<br/>
      ✔ checks in a car (64104ms)<br/>
    Deposit token and make payment<br/>
      ✔ deposits token (1480ms)<br/>
      ✔ makes a payment (73486ms)<br/>
    edit car<br/>
      ✔ shou1d edit an existing car‘s metadata with valid parameters (3086ms)<br/>
      1) shou1d edit an existing car's status<br/>

    Events emitted during test:<br/>
    ---------------------------<br/>

    [object Object].CarAdded(<br/>
      id: <indexed> 1 (type: uint256),<br/>
      name: 'Tesla Model S' (type: string),<br/>
      imgUrl: 'example img url' (type: string),<br/>
      rentFee: 10 (type: uint256),<br/>
      saleFee: 50000 (type: uint256)<br/>
    )<br/>

    [object Object].CarStatusEdited(<br/>
      id: <indexed> 1 (type: uint256),<br/>
      status: CarRentalPlatform.Status.Retired (type: enum CarRentalPlatform.Status)<br/>
    )<br/>


    ---------------------------<br/>
    w1thdraw balance<br/>
      ✔ shou1d send the desired amount of tokens to the user (5454ms)<br/>
      ✔ shou1d send the desired amount of tokens to the owner (69023ms)<br/>


  9 passing (4m)<br/>
  1 failing<br/>

  1) Contract: CarRentalPlatform<br/>
       edit car<br/>
         shou1d edit an existing car's status:<br/>
     TypeError: assert.aqua1 is not a function<br/>
      at Context.<anonymous> (test\CarRentalPlatform.js:97:12)<br/>
      at processTicksAndRejections (node:internal/process/task_queues:95:5)<br/>



PS D:\myproject\blockchainrisein> npm run test<br/>

> bsc-starter-box@1.0.0 test<br/>
> truffle test<br/>

Using network 'development'.<br/>


Compiling your contracts...<br/>
===========================<br/>
> Compiling .\contracts\bsc\CarRentalPlatform.sol<br/>
> Compiling .\node_modules\@openzeppelin\contracts\security\ReentrancyGuard.sol<br/>
> Compiling .\node_modules\@openzeppelin\contracts\utils\Counters.sol<br/>
> Artifacts written to C:\Users\shash\AppData\Local\Temp\test--21192-zpMSoXUdr5eC<br/>
> Compiled successfully using:<br/>
   - solc: 0.8.12+commit.f00d7308.Emscripten.clang<br/>
carRentalPlatformAddress = 0x0aaC9Aa962dA51c930c02A61Df7eD21CE455eE38<br/>


  Contract: CarRentalPlatform<br/>
    Add user and car<br/>
      ✔ adds a new user (826ms)<br/>
      ✔ adds a car (1255ms)<br/>
    Check out and check in car<br/>
      ✔ Check out a car (3012ms)<br/>
      ✔ checks in a car (64418ms)<br/>
    Deposit token and make payment<br/>
      ✔ deposits token (1769ms)<br/>
      ✔ makes a payment (73690ms)<br/>
    edit car<br/>
      ✔ shou1d edit an existing car‘s metadata with valid parameters (2816ms)<br/>
      ✔ shou1d edit an existing car's status (2603ms)<br/>
    w1thdraw balance<br/>
      ✔ shou1d send the desired amount of tokens to the user (6271ms)<br/>
      ✔ shou1d send the desired amount of tokens to the owner (70075ms)<br/>


  10 passing (4m)<br/>



truffle unbox bnb-chain/BSC-Truffle-Starter-Box<br/>
npm i @openzeppelin/contracts@4.9.3<br/>
npm run compile<br/>
npm run test<br/>
npm run compile:bsc<br/>
npm run test:bsc bscTestnet<br/>
npm run migrate:bscTestnet<br/>
npx create-react-app my-project<br/>
npm install -D tailwindcss<br/>
https://docs.bscscan.com/misc-tools-and-utilities/public-rpc-nodes<br/>
