# Benchmark Results

Performance comparison between govalid and popular Go validation libraries.

## Latest Results

**Benchmarked on:** 2025-10-30  
**Platform:** Linux 6.11.0-1018-azure x86_64  
**Go version:** go1.24.3

## Raw Benchmark Data

```
BenchmarkGoValidAlpha-4                    	122547262	         9.765 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundAlpha-4               	 2535282	       472.0 ns/op	       0 B/op	       0 allocs/op
BenchmarkAsaskevichGovalidatorAlpha-4      	10918437	       109.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateAlpha-4             	   56576	     22886 ns/op	   16937 B/op	     101 allocs/op
BenchmarkGoValidCELConcurrent-4            	646835864	         1.863 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELMultipleExpressions-4   	296196409	         4.050 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELBasic-4                 	296225667	         4.051 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELCrossField-4            	349953122	         3.430 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELStringLength-4          	1000000000	         1.000 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidCELNumericComparison-4     	1000000000	         1.000 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidEmail-4                    	21648187	        55.03 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundEmail-4               	 1000000	      1099 ns/op	      88 B/op	       5 allocs/op
BenchmarkGoValidatorEmail-4                	 1278758	       938.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateEmail-4             	   69783	     17176 ns/op	   15853 B/op	      76 allocs/op
BenchmarkGoValidEnum-4                     	275015901	         4.359 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGT-4                       	482042595	         2.489 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGT-4                  	11289252	       106.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorGT-4                   	13762742	        88.62 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidGTE-4                      	480776184	         2.490 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundGTE-4                 	11289816	       106.4 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLength-4                   	160764488	         7.464 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLength-4              	 9649472	       124.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorLength-4               	 4842925	       247.2 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateLength-4            	   74746	     16188 ns/op	   15616 B/op	      79 allocs/op
BenchmarkGoValidLT-4                       	481547488	         2.491 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLT-4                  	11205666	       106.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidLTE-4                      	428645124	         2.801 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundLTE-4                 	10924106	       109.8 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxItems-4                 	183743127	         6.530 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxItems-4            	 8349056	       143.7 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMaxLength-4                	35984146	        33.33 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMaxLength-4           	 8628926	       139.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMaxLength-4            	 4208384	       284.0 ns/op	      32 B/op	       2 allocs/op
BenchmarkGookitValidateMaxLength-4         	   73158	     16277 ns/op	   15648 B/op	      81 allocs/op
BenchmarkGoValidMinItems-4                 	202711941	         5.919 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinItems-4            	 8306034	       144.3 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidMinLength-4                	52181313	        23.01 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundMinLength-4           	10106606	       119.2 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorMinLength-4            	 4231282	       282.0 ns/op	      32 B/op	       2 allocs/op
BenchmarkGoValidNumeric-4                  	157341040	         7.654 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundNumeric-4             	12126573	        99.01 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorNumeric-4              	 9406914	       128.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateNumeric-4           	   71161	     16687 ns/op	   15574 B/op	      78 allocs/op
BenchmarkGoValidRequired-4                 	320437843	         3.738 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundRequired-4            	 8014425	       149.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorRequired-4             	642025956	         1.868 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateRequired-4          	   76129	     15652 ns/op	   15488 B/op	      73 allocs/op
BenchmarkGoValidURL-4                      	20689268	        57.74 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundURL-4                 	 2475303	       489.5 ns/op	     144 B/op	       1 allocs/op
BenchmarkGoValidatorURL-4                  	  103057	     11775 ns/op	     146 B/op	       1 allocs/op
BenchmarkGookitValidateURL-4               	   70498	     16866 ns/op	   15681 B/op	      77 allocs/op
BenchmarkGoValidUUID-4                     	24698126	        48.55 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoPlaygroundUUID-4                	 2699631	       447.6 ns/op	       0 B/op	       0 allocs/op
BenchmarkGoValidatorUUID-4                 	 3578132	       343.0 ns/op	       0 B/op	       0 allocs/op
BenchmarkGookitValidateUUID-4              	   70965	     16816 ns/op	   15542 B/op	      76 allocs/op
```

## Performance Comparison

| Validator | govalid | go-playground | vs go-playground | asaskevich/govalidator | vs asaskevich | gookit/validate | vs gookit |
|-----------|---------|---------------|------------------|----------------------|---------------|----------------|----------|
| LTE | 2.801 / 0 allocs | 109.8 / 0 allocs | **39.2x** | N/A | N/A | N/A | N/A |
| Enum | 4.359 / 0 allocs | N/A | N/A | N/A | N/A | N/A | N/A |
| Email | 55.03 / 0 allocs | 1099 / 88 B / 5 allocs | **20.0x** | 938.8 / 0 allocs | **17.1x** | 17176 / 15853 B / 76 allocs | **312.1x** |
| GTE | 2.490 / 0 allocs | 106.4 / 0 allocs | **42.7x** | N/A | N/A | N/A | N/A |
| MinLength | 23.01 / 0 allocs | 119.2 / 0 allocs | **5.2x** | 282.0 / 32 B / 2 allocs | **12.3x** | N/A | N/A |
| UUID | 48.55 / 0 allocs | 447.6 / 0 allocs | **9.2x** | 343.0 / 0 allocs | **7.1x** | 16816 / 15542 B / 76 allocs | **346.4x** |
| MaxItems | 6.530 / 0 allocs | 143.7 / 0 allocs | **22.0x** | N/A | N/A | N/A | N/A |
| MaxLength | 33.33 / 0 allocs | 139.2 / 0 allocs | **4.2x** | 284.0 / 32 B / 2 allocs | **8.5x** | 16277 / 15648 B / 81 allocs | **488.4x** |
| LT | 2.491 / 0 allocs | 106.8 / 0 allocs | **42.9x** | N/A | N/A | N/A | N/A |
| MinItems | 5.919 / 0 allocs | 144.3 / 0 allocs | **24.4x** | N/A | N/A | N/A | N/A |
| Alpha | 9.765 / 0 allocs | 472.0 / 0 allocs | **48.3x** | 109.4 / 0 allocs | **11.2x** | 22886 / 16937 B / 101 allocs | **2343.7x** |
| Required | 3.738 / 0 allocs | 149.6 / 0 allocs | **40.0x** | 1.868 / 0 allocs | **0.5x** | 15652 / 15488 B / 73 allocs | **4187.3x** |
| Length | 7.464 / 0 allocs | 124.7 / 0 allocs | **16.7x** | 247.2 / 32 B / 2 allocs | **33.1x** | 16188 / 15616 B / 79 allocs | **2168.8x** |
| URL | 57.74 / 0 allocs | 489.5 / 144 B / 1 allocs | **8.5x** | 11775 / 146 B / 1 allocs | **203.9x** | 16866 / 15681 B / 77 allocs | **292.1x** |
| Numeric | 7.654 / 0 allocs | 99.01 / 0 allocs | **12.9x** | 128.6 / 0 allocs | **16.8x** | 16687 / 15574 B / 78 allocs | **2180.2x** |
| GT | 2.489 / 0 allocs | 106.7 / 0 allocs | **42.9x** | 88.62 / 0 allocs | **35.6x** | N/A | N/A |

## CEL Expression Validation (govalid Exclusive)

| CEL Validator | govalid (ns/op) | Allocations |
|---------------|-----------------|-------------|
| CELConcurrent | 1.863 | 0 allocs |
| CELMultipleExpressions | 4.050 | 0 allocs |
| CELBasic | 4.051 | 0 allocs |
| CELCrossField | 3.430 | 0 allocs |
| CELStringLength | 1.000 | 0 allocs |
| CELNumericComparison | 1.000 | 0 allocs |

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
