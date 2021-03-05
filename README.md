# تفاوت IQueryable<T>و IEnumerable<T>
  
1.IEnumerable در فضای نام System.Collections
2.IQueryable در فضای نام System. Linq
3.هر دو مجموعه رو به جلو هستند.
4.IEnumerable از Lazy Load پشتیبانی نمی کند.
5.IQueryable از Lazy Load پشتیبانی می کند.
6.IEnumerable ، In memory است به این ترتیب که ابتدا کل داده را واکشی می کند و فیلتر ها را بر روی کلاینت اعمال می کند.
7.IQueryable سمت سرور است است و داده ها را سمت سرور فیلتر کرده و دیتا ها را واکشی می کند مناسب برای Linq To Sql
