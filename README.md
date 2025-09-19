# 🛒 Mini E-Commerce App (Client + Admin)

Bu layihə **React Router**, **Layouts**, və **CRUD əməliyyatlarını (GET, POST, DELETE, PUT)** praktika etmək üçün hazırlanmış tapşırıqdır.  
Layihə həm **Client**, həm də **Admin** hissələrindən ibarətdir.  

---

## 📌 Tələblər

### 1. Layihənin hazırlanması
- Layihə sıfırdan qurulmalıdır.  
- `vite + react` istifadə olunmalıdır.  
- Router konfiqurasiyası əlavə olunmalıdır.  

---

### 🖥 Client Layout
- `ClientLayout` yaradılmalıdır.  
- Layout daxilində **Navbar (Home, About, Products)** və **Footer** olmalıdır.

#### Route-lar:
- `/` → `HomePage` (salamlayan mətn göstərilməlidir)  
- `/about` → `AboutPage`  
- `/products` → `ProductsPage` (API-dən gələn məhsullar siyahısı göstərilməlidir)  
- `/products/:id` → `ProductDetailPage` (seçilmiş məhsulun detalları göstərilməlidir)  

---

### ⚙️ Admin Layout
- `AdminLayout` yaradılmalıdır.  
- Layout daxilində **Sidebar (Dashboard, Products, Categories)** olmalıdır.  

#### Route-lar:
- `/admin` → `Dashboard`  
- `/admin/products` → `ProductsList` (**GET** – məhsullar siyahısı)  
- `/admin/products/new` → `AddProduct` (**POST** – yeni məhsul əlavə etmə)  
- `/admin/products/:id` → `ProductDetail`  
- `/admin/products/:id/edit` → `EditProduct` (**PUT** – məhsulu yeniləmə)  
- `/admin/products/:id/delete` → `DeleteProduct` (**DELETE** – məhsulu silmə)  

Eyni qayda ilə `/admin/categories` üçün də CRUD əməliyyatları qurulmalıdır.  

---

### 📡 API əməliyyatları
Backend üçün fake API istifadə olunmalıdır:  
👉 [JSONPlaceholder](https://jsonplaceholder.typicode.com) və ya `json-server`  

- **GET** → bütün məhsullar / kateqoriyalar siyahıda göstərilməlidir.  
- **POST** → form vasitəsilə yeni məhsul / kateqoriya əlavə olunmalıdır.  
- **DELETE** → elementin yanında **Sil** düyməsi ilə silinməlidir.  
- **PUT (Bonus)** → məhsul / kateqoriya redaktə olunmalıdır.  

---

### 🔑 Qaydalar
- `useState` və `useEffect` istifadə olunmalıdır.  
- `Link` və `Route` ilə səhifələr arasında gediş-gəliş qurulmalıdır.  
- `ClientLayout` və `AdminLayout` ayrı yaradılmalıdır və uşaq route-lar həmin layout altında işləməlidir.  
- UI üçün `react-icons` istifadə edilməlidir.  

---

- <img width="932" height="593" alt="image" src="https://github.com/user-attachments/assets/9fda14a4-0963-4094-a2e3-73cad1e456ef" />

