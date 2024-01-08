# FinCalc (Excel)

## Usage

1. Download `FinCalc.xlam` file from code section.
2. Open a new Excel workbook.
3. Go to `File > Options > Customize Ribbon` then check the `Developer` Ribbon and click on `OK`. Now, You are able to see `Developer` Ribbon in your workbook.
4. Go to `Developer > Excel Add-ins > Browse` and open `FinCalc.xlam` file.
5. Check `FinCalc` in `Add-ins available` and click on `OK`.
6. You can use the `FinCalc` formulas in your cells.

## Examples

| Input                   | Output |
|-------------------------|:------:|
| =FinCalc_P2F(10%,1)     |  1.1   |
| =100*FinCalc_P2F(10%,1) |  110   |

## Factors

| Factor        | Excel Formula        | Example                 |
|---------------|----------------------|-------------------------|
| (F/P,i%,n)    | FinCalc_P2F(i%,n)    | =FinCalc_P2F(10%,1)     |
| (P/F,i%,n)    | FinCalc_F2P(i%,n)    | =FinCalc_F2P(10%,1)     |
| (A/F,i%,n)    | FinCalc_F2A(i%,n)    | =FinCalc_F2A(10%,1)     |
| (A/P,i%,n)    | FinCalc_P2A(i%,n)    | =FinCalc_P2A(10%,1)     |
| (F/A,i%,n)    | FinCalc_A2F(i%,n)    | =FinCalc_A2F(10%,1)     |
| (F/A,i%,j%,n) | FinCalc_A2F(i%,j%,n) | =FinCalc_A2F(10%,20%,1) |
| (P/A,i%,n)    | FinCalc_A2P(i%,n)    | =FinCalc_A2P(10%,1)     |
| (P/A,i%,j%,n) | FinCalc_A2P(i%,j%,n) | =FinCalc_A2P(10%,20%,1) |
| (P/G,i%,n)    | FinCalc_G2P(i%,n)    | =FinCalc_G2P(10%,1)     |
| (F/G,i%,n)    | FinCalc_G2F(i%,n)    | =FinCalc_G2F(10%,1)     |
| (A/G,i%,n)    | FinCalc_G2A(i%,n)    | =FinCalc_G2A(10%,1)     |
