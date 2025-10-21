# 정상 약결합 흐름 정보

### 홈 화면 조회

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 11:38:49.861 | 2025-09-15 11:38:51.128 | http: 200 | GET | http://127.0.0.1:8080/ |
| 2 | frontend | currencyservice | 2025-09-15 11:38:49.934 | 2025-09-15 11:38:49.993 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |
| 3 | frontend | productcatalogservice | 2025-09-15 11:38:49.996 | 2025-09-15 11:38:50.041 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/ListProducts |
| 4 | frontend | cartservice | 2025-09-15 11:38:50.045 | 2025-09-15 11:38:50.895 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 5 | frontend | currencyservice | 2025-09-15 11:38:50.906 | 2025-09-15 11:38:50.956 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 6 | frontend | currencyservice | 2025-09-15 11:38:50.957 | 2025-09-15 11:38:50.959 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 7 | frontend | currencyservice | 2025-09-15 11:38:50.960 | 2025-09-15 11:38:50.962 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 8 | frontend | currencyservice | 2025-09-15 11:38:50.962 | 2025-09-15 11:38:50.971 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 9 | frontend | currencyservice | 2025-09-15 11:38:50.972 | 2025-09-15 11:38:50.975 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 10 | frontend | currencyservice | 2025-09-15 11:38:50.975 | 2025-09-15 11:38:50.978 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 11 | frontend | currencyservice | 2025-09-15 11:38:50.979 | 2025-09-15 11:38:50.981 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 12 | frontend | currencyservice | 2025-09-15 11:38:50.982 | 2025-09-15 11:38:50.984 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 13 | frontend | currencyservice | 2025-09-15 11:38:50.985 | 2025-09-15 11:38:50.988 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 14 | frontend | adservice | 2025-09-15 11:38:51.031 | 2025-09-15 11:38:51.119 | grpc: 0 | POST | http://adservice:9555/hipstershop.AdService/GetAds |    

## 상품 상세 조회

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 11:38:58.883 | 2025-09-15 11:38:59.228 | http: 200 | GET | http://127.0.0.1:8080/product/OLJCESPC7Z |
| 2 | frontend | productcatalogservice | 2025-09-15 11:38:58.952 | 2025-09-15 11:38:58.991 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 3 | frontend | currencyservice | 2025-09-15 11:38:58.991 | 2025-09-15 11:38:59.002 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |
| 4 | frontend | cartservice | 2025-09-15 11:38:59.003 | 2025-09-15 11:38:59.033 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 5 | frontend | currencyservice | 2025-09-15 11:38:59.034 | 2025-09-15 11:38:59.039 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 6 | frontend | recommendationservice | 2025-09-15 11:38:59.040 | 2025-09-15 11:38:59.148 | grpc: 0 | POST | http://recommendationservice:8080/hipstershop.RecommendationService/ListRecommendations |
| 7 | recommendationservice | productcatalogservice | 2025-09-15 11:38:59.118 | 2025-09-15 11:38:59.134 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/ListProducts |      
| 8 | frontend | productcatalogservice | 2025-09-15 11:38:59.150 | 2025-09-15 11:38:59.152 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 9 | frontend | productcatalogservice | 2025-09-15 11:38:59.153 | 2025-09-15 11:38:59.154 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 10 | frontend | productcatalogservice | 2025-09-15 11:38:59.161 | 2025-09-15 11:38:59.163 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 11 | frontend | productcatalogservice | 2025-09-15 11:38:59.163 | 2025-09-15 11:38:59.166 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 12 | frontend | productcatalogservice | 2025-09-15 11:38:59.167 | 2025-09-15 11:38:59.169 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 13 | frontend | adservice | 2025-09-15 11:38:59.169 | 2025-09-15 11:38:59.219 | grpc: 0 | POST | http://adservice:9555/hipstershop.AdService/GetAds |

### 장바구니 조회

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 11:39:04.687 | 2025-09-15 11:39:04.935 | http: 200 | GET | http://127.0.0.1:8080/cart |
| 2 | frontend | currencyservice | 2025-09-15 11:39:04.725 | 2025-09-15 11:39:04.764 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |
| 3 | frontend | cartservice | 2025-09-15 11:39:04.766 | 2025-09-15 11:39:04.811 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 4 | frontend | recommendationservice | 2025-09-15 11:39:04.811 | 2025-09-15 11:39:04.856 | grpc: 0 | POST | http://recommendationservice:8080/hipstershop.RecommendationService/ListRecommendations |
| 5 | recommendationservice | productcatalogservice | 2025-09-15 11:39:04.823 | 2025-09-15 11:39:04.851 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/ListProducts |      
| 6 | frontend | productcatalogservice | 2025-09-15 11:39:04.857 | 2025-09-15 11:39:04.862 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 7 | frontend | productcatalogservice | 2025-09-15 11:39:04.862 | 2025-09-15 11:39:04.864 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 8 | frontend | productcatalogservice | 2025-09-15 11:39:04.864 | 2025-09-15 11:39:04.866 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 9 | frontend | productcatalogservice | 2025-09-15 11:39:04.867 | 2025-09-15 11:39:04.868 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 10 | frontend | productcatalogservice | 2025-09-15 11:39:04.869 | 2025-09-15 11:39:04.872 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 11 | frontend | shippingservice | 2025-09-15 11:39:04.877 | 2025-09-15 11:39:04.924 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/GetQuote |
| 12 | frontend | currencyservice | 2025-09-15 11:39:04.927 | 2025-09-15 11:39:04.931 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |

### 장바구니 상품 추가

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 11:39:09.186 | 2025-09-15 11:39:09.373 | http: 302 | POST | http://127.0.0.1:8080/cart |
| 2 | frontend | productcatalogservice | 2025-09-15 11:39:09.234 | 2025-09-15 11:39:09.282 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 3 | frontend | cartservice | 2025-09-15 11:39:09.283 | 2025-09-15 11:39:09.366 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/AddItem |

### 장바구니 비우기

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 11:39:13.108 | 2025-09-15 11:39:13.181 | http: 302 | POST | http://127.0.0.1:8080/cart/empty |
| 2 | frontend | cartservice | 2025-09-15 11:39:13.139 | 2025-09-15 11:39:13.171 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/EmptyCart |

### 장바구니 상품 결제

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 11:39:19.907 | 2025-09-15 11:39:20.344 | http: 200 | POST | http://127.0.0.1:8080/cart/checkout |
| 2 | frontend | checkoutservice | 2025-09-15 11:39:19.953 | 2025-09-15 11:39:20.243 | grpc: 0 | POST | http://checkoutservice:5050/hipstershop.CheckoutService/PlaceOrder |
| 3 | checkoutservice | cartservice | 2025-09-15 11:39:20.004 | 2025-09-15 11:39:20.032 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 4 | checkoutservice | shippingservice | 2025-09-15 11:39:20.036 | 2025-09-15 11:39:20.075 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/GetQuote |
| 5 | checkoutservice | currencyservice | 2025-09-15 11:39:20.078 | 2025-09-15 11:39:20.119 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 6 | checkoutservice | paymentservice | 2025-09-15 11:39:20.121 | 2025-09-15 11:39:20.205 | grpc: 0 | POST | http://paymentservice:50051/hipstershop.PaymentService/Charge |
| 7 | checkoutservice | shippingservice | 2025-09-15 11:39:20.207 | 2025-09-15 11:39:20.212 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/ShipOrder |
| 8 | checkoutservice | cartservice | 2025-09-15 11:39:20.213 | 2025-09-15 11:39:20.220 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/EmptyCart |
| 9 | checkoutservice | emailservice | 2025-09-15 11:39:20.222 | 2025-09-15 11:39:20.234 | grpc: 0 | POST | http://emailservice:5000/hipstershop.EmailService/SendOrderConfirmation |
| 10 | frontend | recommendationservice | 2025-09-15 11:39:20.257 | 2025-09-15 11:39:20.321 | grpc: 0 | POST | http://recommendationservice:8080/hipstershop.RecommendationService/ListRecommendations |
| 11 | recommendationservice | productcatalogservice | 2025-09-15 11:39:20.283 | 2025-09-15 11:39:20.315 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/ListProducts |     
| 12 | frontend | productcatalogservice | 2025-09-15 11:39:20.322 | 2025-09-15 11:39:20.327 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 13 | frontend | productcatalogservice | 2025-09-15 11:39:20.327 | 2025-09-15 11:39:20.328 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 14 | frontend | productcatalogservice | 2025-09-15 11:39:20.329 | 2025-09-15 11:39:20.330 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 15 | frontend | productcatalogservice | 2025-09-15 11:39:20.330 | 2025-09-15 11:39:20.332 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 16 | frontend | productcatalogservice | 2025-09-15 11:39:20.332 | 2025-09-15 11:39:20.334 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 17 | frontend | currencyservice | 2025-09-15 11:39:20.335 | 2025-09-15 11:39:20.339 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |



# 오류 발생 약결합 흐름 정보

### 서비스 도달 실패 오류 - 장바구니 조회

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 15:09:59.830 | 2025-09-15 15:10:04.551 | http: 503 | GET | http://127.0.0.1:8080/cart |
| 2 | frontend | currencyservice | 2025-09-15 15:09:59.893 | 2025-09-15 15:09:59.934 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |
| 3 | frontend | cartservice | 2025-09-15 15:09:59.938 | 2025-09-15 15:10:00.838 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 4 | frontend | recommendationservice | 2025-09-15 15:10:00.845 | 2025-09-15 15:10:04.522 | grpc: 14 | POST | http://recommendationservice:8080/hipstershop.RecommendationService/ListRecommendations |


### 연결 지점 불일치 오류 - 장바구니 조회

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 16:51:11.981 | 2025-09-15 16:51:12.758 | http: 500 | GET | http://127.0.0.1:8080/cart |
| 2 | frontend | currencyservice | 2025-09-15 16:51:12.014 | 2025-09-15 16:51:12.041 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |
| 3 | frontend | cartservice | 2025-09-15 16:51:12.044 | 2025-09-15 16:51:12.691 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 4 | frontend | recommendationservice | 2025-09-15 16:51:12.695 | 2025-09-15 16:51:12.749 | grpc: 5 | POST | http://recommendationservice:8080/hipstershop.RecommendationService/ListRecommendations |
| 5 | recommendationservice | productcatalogservice | 2025-09-15 16:51:12.726 | 2025-09-15 16:51:12.735 | grpc: 12 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/ListPro |

### 데이터 명세 불일치 오류 - 장바구니 상품 결제 

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 21:25:25.841 | 2025-09-15 21:25:26.248 | http: 500 | POST | http://127.0.0.1:8080/cart/checkout |
| 2 | frontend | checkoutservice | 2025-09-15 21:25:25.863 | 2025-09-15 21:25:26.241 | grpc: 3 | POST | http://checkoutservice:5050/hipstershop.CheckoutService/PlaceOrder |

### 시간적 제약 위반 오류 - 홈 화면 조회

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-16 00:13:00.451 | 2025-09-16 00:13:00.531 | http: 503 | GET | http://127.0.0.1:8080/ |
| 2 | frontend | currencyservice | 2025-09-16 00:13:00.482 | 2025-09-16 00:13:00.523 | http: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/GetSupportedCurrencies |
| 3 | frontend | productcatalogservice | 2025-09-16 00:13:00.482 | 2025-09-16 00:13:00.515 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/ListProducts |

### 상태 일관성 오류 - 장바구니 상품 추가

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 22:17:24.517 | 2025-09-15 22:17:30.729 | http: 500 | POST | http://127.0.0.1:8080/cart |
| 2 | frontend | productcatalogservice | 2025-09-15 22:17:24.700 | 2025-09-15 22:17:24.798 | grpc: 0 | POST | http://productcatalogservice:3550/hipstershop.ProductCatalogService/GetProduct |
| 3 | frontend | cartservice | 2025-09-15 22:17:24.806 | 2025-09-15 22:17:30.662 | grpc: 9 | POST | http://cartservice:7070/hipstershop.CartService/AddItem |

### 복합 기능 수행 오류 - 장바구니 상품 결제

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 22:50:48.131 | 2025-09-15 22:50:49.457 | http: 500 | POST | http://127.0.0.1:8080/cart/checkout |
| 2 | frontend | checkoutservice | 2025-09-15 22:50:48.175 | 2025-09-15 22:50:49.423 | grpc: 14 | POST | http://checkoutservice:5050/hipstershop.CheckoutService/PlaceOrder |
| 3 | checkoutservice | cartservice | 2025-09-15 22:50:48.200 | 2025-09-15 22:50:49.130 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 4 | checkoutservice | shippingservice | 2025-09-15 22:50:49.158 | 2025-09-15 22:50:49.186 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/GetQuote |
| 5 | checkoutservice | currencyservice | 2025-09-15 22:50:49.188 | 2025-09-15 22:50:49.237 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 6 | checkoutservice | paymentservice | 2025-09-15 22:50:49.240 | 2025-09-15 22:50:49.298 | grpc: 0 | POST | http://paymentservice:50051/hipstershop.PaymentService/Charge |
| 7 | checkoutservice | shippingservice | 2025-09-15 22:50:49.302 | 2025-09-15 22:50:49.308 | grpc: 2 | POST | http://shippingservice:50051/hipstershop.ShippingService/ShipOrder |
| 8 | checkoutservice | cartservice | 2025-09-15 22:50:49.338 | 2025-09-15 22:50:49.360 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 9 | checkoutservice | shippingservice | 2025-09-15 22:50:49.361 | 2025-09-15 22:50:49.364 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/GetQuote |
| 10 | checkoutservice | currencyservice | 2025-09-15 22:50:49.365 | 2025-09-15 22:50:49.369 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 11 | checkoutservice | paymentservice | 2025-09-15 22:50:49.369 | 2025-09-15 22:50:49.372 | grpc: 0 | POST | http://paymentservice:50051/hipstershop.PaymentService/Charge |
| 12 | checkoutservice | shippingservice | 2025-09-15 22:50:49.373 | 2025-09-15 22:50:49.375 | grpc: 2 | POST | http://shippingservice:50051/hipstershop.ShippingService/ShipOrder |
| 13 | checkoutservice | cartservice | 2025-09-15 22:50:49.404 | 2025-09-15 22:50:49.407 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 14 | checkoutservice | shippingservice | 2025-09-15 22:50:49.407 | 2025-09-15 22:50:49.410 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/GetQuote |
| 15 | checkoutservice | currencyservice | 2025-09-15 22:50:49.410 | 2025-09-15 22:50:49.415 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 16 | checkoutservice | paymentservice | 2025-09-15 22:50:49.415 | 2025-09-15 22:50:49.419 | grpc: 0 | POST | http://paymentservice:50051/hipstershop.PaymentService/Charge |
| 17 | checkoutservice | shippingservice | 2025-09-15 22:50:49.419 | 2025-09-15 22:50:49.421 | grpc: 2 | POST | http://shippingservice:50051/hipstershop.ShippingService/ShipOrder |

### 데이터 명세 불일치 오류 - 장바구니 상품 결제

| Sequence | Send Service | Receive Service | Start Time | End Time | Status Code | Method | URL |
|----------|--------------|-----------------|------------|----------|-------------|--------|-----|
| 1 | user | frontend | 2025-09-15 23:44:18.329 | 2025-09-15 23:44:19.262 | http: 500 | POST | http://127.0.0.1:8080/cart/checkout |
| 2 | frontend | checkoutservice | 2025-09-15 23:44:18.384 | 2025-09-15 23:44:19.252 | grpc: 13 | POST | http://checkoutservice:5050/hipstershop.CheckoutService/PlaceOrder |
| 3 | checkoutservice | cartservice | 2025-09-15 23:44:18.419 | 2025-09-15 23:44:19.118 | grpc: 0 | POST | http://cartservice:7070/hipstershop.CartService/GetCart |
| 4 | checkoutservice | shippingservice | 2025-09-15 23:44:19.122 | 2025-09-15 23:44:19.144 | grpc: 0 | POST | http://shippingservice:50051/hipstershop.ShippingService/GetQuote |
| 5 | checkoutservice | currencyservice | 2025-09-15 23:44:19.147 | 2025-09-15 23:44:19.194 | grpc: 0 | POST | http://currencyservice:7000/hipstershop.CurrencyService/Convert |
| 6 | checkoutservice | paymentservice | 2025-09-15 23:44:19.198 | 2025-09-15 23:44:19.246 | grpc: 11 | POST | http://paymentservice:50051/hipstershop.PaymentService/Charge |