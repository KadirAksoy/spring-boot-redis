## Redis 


@Cacheable: Bu annotasyon, bir metodu önbelleğe alma işlemi için işaretler. Metodun sonucu, önbellekte saklanır ve aynı parametrelerle çağrıldığında yeniden hesaplanmadan önbellekteki değer döndürülür.

@CachePut: Bu annotasyon, belirli bir anahtarla bir önbellek girdisini güncellemek veya eklemek için kullanılır. Bu, her zaman metodu çağıran ve sonucunu önbelleğe ekleyen bir işlev sağlar.

@CacheEvict: Bu annotasyon, belirli bir anahtarı veya tüm önbelleği temizlemek için kullanılır. Yani, metodu çağırarak önbellekteki belirli bir girdiyi veya tüm girdileri siler.
