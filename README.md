# stock-market-data-extraction
The project aims to collect data from candle stick images provided by several brokers for equity markets. The above was done using image processing and ocr techniques. 
![ibul_hr_19thDec22_9thJan23](https://github.com/DhanuSingh/stock-market-data-extraction/assets/50412680/81a4dd66-7e88-4640-99c9-b7ed0e73af7e)
Processing the above image to extract data from it
Contour detection of red and green candles
![cntrs_red](https://github.com/DhanuSingh/stock-market-data-extraction/assets/50412680/f44cb6ff-d44c-4a93-aa6f-92a12bb24552)
![cntrs_green](https://github.com/DhanuSingh/stock-market-data-extraction/assets/50412680/dbc1fd86-900d-4cd8-9ed8-83f0067ae104)
Doing calibration for pixel to price and time using OCR
![price_time_calibration](https://github.com/DhanuSingh/stock-market-data-extraction/assets/50412680/f09df9bd-3b36-4187-a4e7-b613a7f34492)
Getting the price using the above calibration for each candles.
![thresh_red_price_check](https://github.com/DhanuSingh/stock-market-data-extraction/assets/50412680/e3dedaa6-7742-42fd-9431-d402a3f8f7c0)
![thresh_green_price_check](https://github.com/DhanuSingh/stock-market-data-extraction/assets/50412680/afdde2f4-6b0e-4b6f-b071-e389afb45907)
Finally converting this to csv data for strategy formulation.

