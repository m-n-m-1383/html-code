# html-code
<!DOCTYPE html>
<html lang="UTF-8" dir="rtl">
<head>
</head>
<body>
  <table border="2">
    <tr>
      <th>دستورات HTML</th>
      <th>کد HTML</th>
    </tr>
    <tr>
        <td>تگ <code>&lt;a&gt;</code> برای ایجاد لینک‌های اینترنتی یا داخلی در صفحات HTML استفاده می‌شود.</td>
        <td dir="ltr"><code>&lt;a href=" متن نمایشی لینک &lt;" سایت مورد نظر &lt;/a&gt;</code></td>
      </tr>
      <tr>
        <td>تگ <code>&lt;br&gt;</code> برای ایجاد شکست خط و <code>&lt;hr&gt;</code> برای خط افقی استفاده می‌شود.</td>
        <td dir="ltr"><code>متن اول&lt;br&gt;متن دوم<br/><br/></code></tسسd>
      </tr>
    <tr>
      <td>تگ <code>&lt;hr&gt;</code> برای ایجاد خط افقی در صفحه استفاده می‌شود. این تگ نیز خود بسته است و نیازی به تگ بسته ندارد. معمولاً برای جدا کردن بخش‌ها به کار می‌رود.</td>
      <td dir="ltr"><code>&lt;hr&gt;</code></td>
    </tr>
    <tr>
        <td>تگ <code>&lt;div&gt;</code> برای گروه‌بندی و تقسیم‌بندی المان‌های مختلف در صفحه HTML استفاده می‌شود. این تگ معمولاً برای طراحی ساختار صفحه یا بخش‌های مختلف استفاده می‌شود.</td>
        <td dir="ltr"><code>&lt;div&gt;محتوا&lt;/div&gt;</code></td>
      </tr>
    <tr>
      <th> متن ها و توضیح </th>
      <th>کد HTML</th>
    </tr>
    <tr>
        <td>تگ <code>&lt;p&gt;</code> برای ایجاد پاراگراف استفاده می‌شود.</td>
        <td dir="ltr"><code>&lt;p&gt;این یک پاراگراف نمونه است.&lt;/p&gt;</code></td>
      </tr>
    <tr>
      <td>تگ <code>&lt;h1&gt;</code> برای ایجاد بزرگترین عنوان استفاده می‌شود. این تگ معمولاً برای عناوین اصلی صفحه یا بخش‌های مهم به‌کار می‌رود.</td>
      <td dir="ltr"><code>&lt;h1&gt;عنوان اصلی&lt;/h1&gt;</code></td>
    </tr>
    <tr>
      <td>تگ‌های <code>&lt;h2&gt;</code> تا <code>&lt;h6&gt;</code> برای عناوین با اندازه‌های کوچکتر به ترتیب استفاده می‌شوند.</td>
      <td dir="ltr">
        <code>&lt;h2&gt;عنوان دوم&lt;/h2&gt;<br/>
        &lt;h3&gt;عنوان سوم&lt;/h3&gt;<br/>
        &lt;h4&gt;عنوان چهارم&lt;/h4&gt;<br/>
        &lt;h5&gt;عنوان پنجم&lt;/h5&gt;<br/>
        &lt;h6&gt;عنوان ششم&lt;/h6&gt;</code>
      </td>
    </tr>
    <tr>
      <th> لیست‌ها و توضیح </th>
      <th>کد HTML</th>
    </tr>
    <tr>
        <td>تگ <code>&lt;ol&gt;</code> برای لیست مرتب و <code>&lt;ul&gt;</code> برای لیست غیرمرتب استفاده می‌شود. آیتم‌ها با <code>&lt;li&gt;</code> تعریف می‌شوند.</td>
        <td dir="ltr">
        <code>
            &lt;ol start="5" type="I"&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;آیتم 1&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;آیتم 2&lt;/li&gt;<br/>
            &lt;/ol&gt;<br/><br/>
            &lt;ul type="square"&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;آیتم 1&lt;/li&gt;<br/>
            &nbsp;&nbsp;&lt;li&gt;آیتم 2&lt;/li&gt;<br/>
            &lt;/ul&gt;
        </code>
        </td>
      </tr>
    <tr>
        <td>تگ‌های <code>&lt;dl&gt;</code> (لیست تعریفی)، <code>&lt;dt&gt;</code> (عنوان کلمه) و <code>&lt;dd&gt;</code> (تعریف کلمه) استفاده می‌شوند.</td>
        <td dir="ltr">
          <code>
            &lt;dl&gt;<br/>
            &nbsp;&nbsp;&lt;dt&gt;HTML&lt;/dt&gt;<br/>
            &nbsp;&nbsp;&lt;dd&gt;زبان نشانه‌گذاری صفحات وب&lt;/dd&gt;<br/>
            &lt;/dl&gt;
          </code>
        </td>
      </tr>
    <tr>
      <th>اضافه کردن عکس و ویدیو</th>
      <th>کد HTML</th>
    </tr>
    <tr>
        <td>تگ <code>&lt;img&gt;</code> برای درج تصویر در صفحه استفاده می‌شود. ویژگی‌های مهم آن <code>src</code>، <code>alt</code>، <code>width</code> و <code>height</code> هستند.</td>
        <td dir="ltr"><code>&lt;img src="image.jpg" alt="توضیح تصویر" width="500" height="300"&gt;</code></td>
      </tr>
      <tr>
        <td>تگ <code>&lt;video&gt;</code> برای نمایش ویدیو به همراه ویژگی‌هایی مثل <code>controls</code> و <code>autoplay</code> است. تگ <code>&lt;source&gt;</code> منابع ویدیویی را تعریف می‌کند و <code>&lt;track&gt;</code> زیرنویس‌ها را.</td>
        <td dir="ltr">
          <code>
            &lt;video controls width="600"&gt;<br/>
            &nbsp;&nbsp;&lt;source src="movie.mp4" type="video/mp4"&gt;<br/>
            &nbsp;&nbsp;&lt;track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English"&gt;<br/>
            &lt;/video&gt;
          </code>
        </td>
      </tr>
    <tr>
    </tr>
    <tr>
        <td>تگ <code>&lt;audio&gt;</code> برای پخش فایل‌های صوتی با ویژگی‌هایی مانند <code>controls</code> و <code>autoplay</code> استفاده می‌شود.</td>
        <td dir="ltr"><code>&lt;audio controls src="audio.mp3"&gt;صدای شما پخش نشد&lt;/audio&gt;</code></td>
      </tr>
    <tr>
      <th>جدول و قابلیت ها</th>
      <th>کد HTML</th>
    </tr>
    <tr>
        <td>تگ <code>&lt;table&gt;</code> برای ساخت جدول، <code>&lt;tr&gt;</code> ردیف‌ها، <code>&lt;th&gt;</code> سلول‌های عنوان و <code>&lt;td&gt;</code> سلول‌های داده استفاده می‌شوند.</td>
        <td dir="ltr">
          <code>
            &lt;table&gt;<br/>
            &nbsp;&nbsp;&lt;tr&gt;&lt;th&gt;عنوان&lt;/th&gt;&lt;/tr&gt;<br/>
            &nbsp;&nbsp;&lt;tr&gt;&lt;td&gt;داده&lt;/td&gt;&lt;/tr&gt;<br/>
            &lt;/table&gt;
          </code>
        </td>
      </tr>
      <tr>
        <td>ویژگی‌های <code>colspan</code> و <code>rowspan</code> برای ترکیب سلول‌ها به ترتیب افقی و عمودی استفاده می‌شوند.</td>
        <td dir="ltr">
          <code>
            &lt;table border="1"&gt;<br/>
            &nbsp;&nbsp;&lt;tr&gt;<br/>
            &nbsp;&nbsp;&nbsp;&nbsp;&lt;td rowspan="2"&gt;سلول rowspan&lt;/td&gt;<br/>
            &nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt;سلول معمولی&lt;/td&gt;<br/>
            &nbsp;&nbsp;&lt;/tr&gt;<br/>
            &nbsp;&nbsp;&lt;tr&gt;<br/>
            &nbsp;&nbsp;&nbsp;&nbsp;&lt;td colspan="2"&gt;سلول colspan&lt;/td&gt;<br/>
            &nbsp;&nbsp;&lt;/tr&gt;<br/>
            &lt;/table&gt;
          </code>
        </td>
        <tr>
            <td>تگ‌های <code>&lt;caption&gt;</code> (عنوان جدول)، <code>&lt;thead&gt;</code> (بخش هدر جدول)، <code>&lt;tbody&gt;</code> (بدنه جدول) و <code>&lt;tfoot&gt;</code> (پاورقی جدول) برای ساختاردهی جدول استفاده می‌شوند.</td>
            <td dir="ltr">
              <code>
                &lt;table&gt;<br/>
                &nbsp;&nbsp;&lt;caption&gt;عنوان جدول&lt;/caption&gt;<br/>
                &nbsp;&nbsp;&lt;thead&gt;&lt;tr&gt;&lt;th&gt;عنوان&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;<br/>
                &nbsp;&nbsp;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;داده&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;<br/>
                &nbsp;&nbsp;&lt;tfoot&gt;&lt;tr&gt;&lt;td&gt;پاورقی&lt;/td&gt;&lt;/tr&gt;&lt;/tfoot&gt;<br/>
                &lt;/table&gt;
              </code>
            </td>
          </tr>
    <tr>
      <th>   فرم و قابلیت ها  </th>
      <th>کد HTML</th>
    </tr>
    <tr>
      <td>تگ <code>&lt;form&gt;</code> برای ایجاد فرم‌ها استفاده می‌شود. ویژگی‌هایی مانند <code>action</code> (مقصد ارسال فرم) و <code>method</code> (نوع متد ارسال) برای تعیین نحوه ارسال فرم استفاده می‌شوند.</td>
      <td dir="ltr"><code>&lt;form action="submit.php" method="post"&gt;  &lt;/form&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;input&gt;</code> برای دریافت ورودی از کاربر استفاده می‌شود. این تگ می‌تواند ویژگی‌های مختلفی مانند <code>type</code>, <code>value</code>, <code>placeholder</code> داشته باشد. نوع ورودی با ویژگی <code>type</code> مشخص می‌شود.</td>
      <td dir="ltr"><code>&lt;input type="text" placeholder="متن ورودی"&gt;</code></td>
    </tr>
    <tr>
      <th>نوع <code>&lt;input&gt;</code> و توضیح</th>
      <th>کد HTML</th>
    </tr>
    <tr>
      <td>نوع <code>text</code>: برای دریافت ورودی متنی از کاربر.</td>
      <td dir="ltr"><code>&lt;input type="text"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>password</code>: برای دریافت ورودی رمز عبور که کاراکترها نمایش داده نمی‌شوند.</td>
      <td dir="ltr"><code>&lt;input type="password"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>email</code>: برای دریافت ورودی ایمیل. اعتبارسنجی ایمیل به‌طور خودکار انجام می‌شود.</td>
      <td dir="ltr"><code>&lt;input type="email"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>number</code>: برای دریافت عدد از کاربر. می‌توان حداقل و حداکثر مقادیر را تعیین کرد.</td>
      <td dir="ltr"><code>&lt;input type="number" min="1" max="100"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>date</code>: برای دریافت تاریخ.</td>
      <td dir="ltr"><code>&lt;input type="date"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>checkbox</code>: برای ایجاد چک‌باکس.</td>
      <td dir="ltr"><code>&lt;input type="checkbox"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>radio</code>: برای ایجاد گزینه‌های انتخابی.</td>
      <td dir="ltr"><code>&lt;input type="radio"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>submit</code>: برای ارسال فرم.</td>
      <td dir="ltr"><code>&lt;input type="submit"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>file</code>: برای انتخاب فایل از کامپیوتر.</td>
      <td dir="ltr"><code>&lt;input type="file"&gt;</code></td>
    </tr>
    <tr>
      <td>نوع <code>range</code>: برای انتخاب یک مقدار در یک بازه از پیش‌تعریف‌شده.</td>
      <td dir="ltr"><code>&lt;input type="range" min="0" max="100"&gt;</code></td>
    </tr>
    <tr>
      <th> ورودی های فرم و توضیح </th>
      <th>کد HTML</th>
    </tr>
    <tr>
      <td>تگ <code>&lt;textarea&gt;</code> برای دریافت ورودی چندخطی از کاربر استفاده می‌شود. ویژگی <code>rows</code> و <code>cols</code> برای تنظیم ابعاد این ورودی به‌کار می‌رود.</td>
      <td dir="ltr"><code>&lt;textarea rows="4" cols="50"&gt;متن اولیه&lt;/textarea&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;button&gt;</code> برای ایجاد دکمه‌ها استفاده می‌شود. این تگ می‌تواند ویژگی‌هایی مثل <code>type</code> (برای تعیین نوع دکمه) و <code>onclick</code> (برای افزودن عملکرد به دکمه) داشته باشد.</td>
      <td dir="ltr"><code>&lt;button type="submit"&gt;ارسال&lt;/button&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;select&gt;</code> برای ایجاد منوی کشویی (dropdown) استفاده می‌شود. در داخل آن از تگ <code>&lt;option&gt;</code> برای تعریف هر آیتم منو استفاده می‌شود.</td>
      <td dir="ltr"><code>&lt;select&gt; &lt;option value="option1"&gt;گزینه 1&lt;/option&gt; &lt;option value="option2"&gt;گزینه 2&lt;/option&gt; &lt;/select&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;option&gt;</code> برای ایجاد هر گزینه در منوی کشویی (<code>&lt;select&gt;</code>) استفاده می‌شود. ویژگی <code>value</code> برای مشخص کردن مقداری که ارسال خواهد شد، استفاده می‌شود.</td>
      <td dir="ltr"><code>&lt;option value="option1"&gt;گزینه 1&lt;/option&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;fieldset&gt;</code> برای گروه‌بندی ورودی‌ها (مثل فرم‌ها) به‌کار می‌رود. معمولاً با تگ <code>&lt;legend&gt;</code> همراه است تا عنوانی برای گروه‌بندی ارائه دهد.</td>
      <td dir="ltr">
        <code>&lt;fieldset&gt; &lt;legend&gt;عنوان گروه&lt;/legend&gt; &lt;input type="text"&gt; &lt;/fieldset&gt;</code>
      </td>
    </tr>
    <tr>
      <td>تگ <code>&lt;legend&gt;</code> برای تعیین عنوان برای گروه‌بندی ورودی‌ها در داخل <code>&lt;fieldset&gt;</code> استفاده می‌شود.</td>
      <td dir="ltr"><code>&lt;legend&gt;عنوان فرم&lt;/legend&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;label&gt;</code> برای تعیین برچسب برای ورودی‌ها استفاده می‌شود. این تگ می‌تواند ویژگی <code>for</code> داشته باشد تا به یک ورودی خاص اشاره کند.</td>
      <td dir="ltr"><code>&lt;label for="input1"&gt;نام: &lt;/label&gt; &lt;input type="text" id="input1"&gt;</code></td>
    </tr>
    <tr>
      <td>تگ <code>&lt;datalist&gt;</code> برای تعیین مجموعه‌ای از گزینه‌ها برای ورودی‌هایی که ویژگی <code>list</code> دارند، استفاده می‌شود.</td>
      <td dir="ltr">
        <code>&lt;input list="browsers"&gt; &lt;datalist id="browsers"&gt; &lt;option value="Chrome"&gt; &lt;option value="Firefox"&gt; &lt;/datalist&gt;</code>
      </td>
    </tr>
  </table>
</body>
</html>
