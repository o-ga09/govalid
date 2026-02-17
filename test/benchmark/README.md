# Benchmark Results

Performance comparison between govalid and popular Go validation libraries.

## Latest Results

**Benchmarked on:** 2026-02-17  
**Platform:** Linux 6.14.0-1017-azure x86_64  
**Go version:** go1.24.3

## Raw Benchmark Data

```
BenchmarkGoValidAlpha-4                    	100000000	        10.81 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundAlpha-4               	 3097386	       387.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkAsaskevichGovalidatorAlpha-4      	12816163	        93.59 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateAlpha-4             	   57882	     20679 ns/op	   16937 B/op	     101 allocs/op
BenchmarkGoValidCELConcurrent-4            	485829447	         2.875 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELMultipleExpressions-4   	375206732	         3.193 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELBasic-4                 	372184057	         3.216 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELCrossField-4            	409974267	         2.904 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELStringLength-4          	1000000000	         1.113 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELNumericComparison-4     	657710166	         1.824 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidEmail-4                    	21504166	        55.93 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundEmail-4               	 1000000	      1041 ns/op	      89 B/op	       5 allocs/op
BenchmarkGoValidatorEmail-4                	 1568718	       782.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateEmail-4             	   62316	     18782 ns/op	   15903 B/op	      76 allocs/op
BenchmarkGoValidEnum-4                     	317168702	         3.779 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGT-4                       	564005976	         2.153 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGT-4                  	11808028	       101.9 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorGT-4                   	15991778	        75.28 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGTE-4                      	566017476	         2.122 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGTE-4                 	12005298	        99.94 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidIPV4-4                     	38165964	        31.53 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundIPV4-4                	10159532	       118.0 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidIPV6-4                     	15242058	        78.66 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundIPV6-4                	 7103809	       168.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLength-4                   	156300784	         7.622 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLength-4              	12080054	        99.46 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorLength-4               	 5383831	       224.3 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateLength-4            	   76201	     15766 ns/op	   15616 B/op	      79 allocs/op
BenchmarkGoValidLT-4                       	565555418	         2.127 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLT-4                  	11429257	       102.0 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLTE-4                      	519243249	         2.315 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLTE-4                 	11630973	       102.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxItems-4                 	276740745	         4.337 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxItems-4            	 9384556	       127.9 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxLength-4                	48902682	        24.54 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxLength-4           	 9470109	       127.9 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMaxLength-4            	 4670932	       256.6 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateMaxLength-4         	   77266	     15625 ns/op	   15648 B/op	      81 allocs/op
BenchmarkGoValidMinItems-4                 	230526828	         5.202 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinItems-4            	 9441330	       126.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMinLength-4                	53871380	        22.27 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinLength-4           	10895834	       110.1 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMinLength-4            	 4712902	       253.7 ns/op	      32 B/op	       2 allocs/op
BenchmarkGoValidNumeric-4                  	133940214	         8.963 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundNumeric-4             	15305283	        78.15 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorNumeric-4              	10824259	       111.0 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateNumeric-4           	   72782	     16233 ns/op	   15575 B/op	      78 allocs/op
BenchmarkGoValidRequired-4                 	377167735	         3.187 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundRequired-4            	 9013494	       132.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorRequired-4             	1000000000	         1.159 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateRequired-4          	   79381	     15071 ns/op	   15488 B/op	      73 allocs/op
BenchmarkGoValidURL-4                      	20468160	        58.41 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundURL-4                 	 2552158	       470.2 ns/op	     144 B/op	       1 allocs/op
BenchmarkGoValidatorURL-4                  	  117193	     10312 ns/op	     145 B/op	       1 allocs/op
BenchmarkGookitValidateURL-4               	   72190	     16229 ns/op	   15681 B/op	      77 allocs/op
BenchmarkGoValidUUID-4                     	28994979	        41.11 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundUUID-4                	 2853392	       420.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorUUID-4                 	 3750536	       320.1 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateUUID-4              	   73563	     16293 ns/op	   15542 B/op	      76 allocs/op
```

## Performance Comparison

| Validator | govalid | go-playground | vs go-playground | asaskevich/govalidator | vs asaskevich | gookit/validate | vs gookit |
|-----------|---------|---------------|------------------|----------------------|---------------|----------------|----------|
| LTE | 2.315 / 0 allocs | 102.7 / 0 allocs | **44.4x** | N/A | N/A | N/A | N/A |
| Enum | 3.779 / 0 allocs | N/A | N/A | N/A | N/A | N/A | N/A |
| Email | 55.93 / 0 allocs | 1041 / 89 B / 5 allocs | **18.6x** | 782.2 / 0 allocs | **14.0x** | 18782 / 15903 B / 76 allocs | **335.8x** |
| GTE | 2.122 / 0 allocs | 99.94 / 0 allocs | **47.1x** | N/A | N/A | N/A | N/A |
| MinLength | 22.27 / 0 allocs | 110.1 / 0 allocs | **4.9x** | 253.7 / 32 B / 2 allocs | **11.4x** | N/A | N/A |
| UUID | 41.11 / 0 allocs | 420.4 / 0 allocs | **10.2x** | 320.1 / 0 allocs | **7.8x** | 16293 / 15542 B / 76 allocs | **396.3x** |
| MaxItems | 4.337 / 0 allocs | 127.9 / 0 allocs | **29.5x** | N/A | N/A | N/A | N/A |
| MaxLength | 24.54 / 0 allocs | 127.9 / 0 allocs | **5.2x** | 256.6 / 32 B / 2 allocs | **10.5x** | 15625 / 15648 B / 81 allocs | **636.7x** |
| LT | 2.127 / 0 allocs | 102.0 / 0 allocs | **48.0x** | N/A | N/A | N/A | N/A |
| MinItems | 5.202 / 0 allocs | 126.8 / 0 allocs | **24.4x** | N/A | N/A | N/A | N/A |
| Alpha | 10.81 / 0 allocs | 387.4 / 0 allocs | **35.8x** | 93.59 / 0 allocs | **8.7x** | 20679 / 16937 B / 101 allocs | **1913.0x** |
| Required | 3.187 / 0 allocs | 132.8 / 0 allocs | **41.7x** | 1.159 / 0 allocs | **0.4x** | 15071 / 15488 B / 73 allocs | **4728.9x** |
| IPV4 | 31.53 / 0 allocs | 118.0 / 0 allocs | **3.7x** | N/A | N/A | N/A | N/A |
| Length | 7.622 / 0 allocs | 99.46 / 0 allocs | **13.0x** | 224.3 / 32 B / 2 allocs | **29.4x** | 15766 / 15616 B / 79 allocs | **2068.5x** |
| IPV6 | 78.66 / 0 allocs | 168.8 / 0 allocs | **2.1x** | N/A | N/A | N/A | N/A |
| URL | 58.41 / 0 allocs | 470.2 / 144 B / 1 allocs | **8.0x** | 10312 / 145 B / 1 allocs | **176.5x** | 16229 / 15681 B / 77 allocs | **277.8x** |
| Numeric | 8.963 / 0 allocs | 78.15 / 0 allocs | **8.7x** | 111.0 / 0 allocs | **12.4x** | 16233 / 15575 B / 78 allocs | **1811.1x** |
| GT | 2.153 / 0 allocs | 101.9 / 0 allocs | **47.3x** | 75.28 / 0 allocs | **35.0x** | N/A | N/A |

## CEL Expression Validation (govalid Exclusive)

| CEL Validator | govalid (ns/op) | Allocations |
|---------------|-----------------|-------------|
| CELConcurrent | 2.875 | 0 allocs |
| CELMultipleExpressions | 3.193 | 0 allocs |
| CELBasic | 3.216 | 0 allocs |
| CELCrossField | 2.904 | 0 allocs |
| CELStringLength | 1.113 | 0 allocs |
| CELNumericComparison | 1.824 | 0 allocs |

CEL (Common Expression Language) support allows complex runtime expressions with near-zero overhead.

## Running Benchmarks

```bash
# Update all benchmark documentation
make sync-benchmarks

# Run benchmarks manually
cd test
go test ./benchmark/ -bench=. -benchmem -benchtime=10s

# Run specific validator benchmarks
go test ./benchmark/ -bench=BenchmarkGoValid{ValidatorName} -benchmem
```
