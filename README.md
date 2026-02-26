<div dir="rtl" align="right" style="text-align: right; font-family: 'Amiri','Scheherazade New','Noto Naskh Arabic','Arial',sans-serif; line-height: 1.9;">

<p>
<a href="https://doi.org/10.5281/zenodo.18793064"><img src="https://zenodo.org/badge/1154947565.svg" alt="DOI"></a>
</p>

<h1>الوحدة M2: علم المناخ الحاسوبي</h1>

<blockquote>
كيف يمكننا تحليل مجموعات بيانات المناخ الشبكية ذات الخصائص المكانية والزمانية؟ وكيف يتم قياس ونمذجة التباين المناخي؟
</blockquote>

<p>
تركّز الوحدة الثانية من
<a href="https://openclimatescience.github.io/curriculum">منهاج علم المناخ المفتوح</a>
على إعداد المتعلمين للعمل مع مجموعات بيانات المناخ الشبكية.
<br>
<strong>بنهاية هذه الوحدة، ينبغي أن تكون قادرًا على:</strong>
</p>

<ul>
  <li>التعرّف على المؤشرات المتاحة للجفاف الأرصادي، وجفاف رطوبة التربة، والطلب الجوي على المياه، وتوازن مياه التربة.</li>
  <li>تحميل وتحليل مجموعات بيانات مناخية كبيرة بكفاءة، بما في ذلك السجلات المناخية طويلة الأمد.</li>
  <li>حساب مؤشر للجفاف.</li>
</ul>

<h2>المحتويات</h2>

<ol>
  <li><a href="https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/01_Managing_Software_Dependencies.ipynb">إدارة تبعيات البرمجيات</a></li>
  <li><a href="https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/02_Working_with_Gridded_Climate_Data.ipynb">العمل مع بيانات المناخ الشبكية</a></li>
  <li><a href="https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/03_Climate_and_Drought_Indices.ipynb">مؤشرات المناخ والجفاف</a></li>
  <li><a href="https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/04_Processing_Long_Climate_Data_Records_Concurrently.ipynb">معالجة سجلات البيانات المناخية طويلة الأمد بالتوازي</a></li>
  <li><a href="https://github.com/OpenClimateScience/M2-Computational-Climate-Science/blob/main/notebooks/05_Creating_a_Reproducible_Climate_Analysis.ipynb">إنشاء تحليل مناخي قابل لإعادة الإنتاج</a></li>
</ol>

<h2>البدء</h2>

<p>
<a href="https://github.com/OpenClimateScience/M1-Open-Climate-Data/blob/main/HOW_TO_INSTALL.md">اطّلع على دليل التثبيت هنا.</a>
</p>

<p>
يمكنك تشغيل دفاتر الملاحظات في هذا المستودع باستخدام
<a href="https://docs.github.com/en/codespaces/overview">Github Codespaces</a>
أو كـ
<a href="https://code.visualstudio.com/docs/devcontainers/containers">حاوية تطوير في VSCode</a>.
بعد تشغيل الحاوية، شغّل Jupyter Notebook عبر:
</p>

<pre><code class="language-sh"># أنشئ كلمة المرور الخاصة بك عند الطلب
jupyter server password

# ثم شغّل Jupyter Notebook؛ أدخل كلمة المرور عند الطلب
jupyter notebook
</code></pre>

<p><strong>يمكن تثبيت مكتبات بايثون المطلوبة للتمارين باستخدام مدير الحزم <code>pip</code>:</strong></p>

<pre><code class="language-sh">pip install xarray netcdf4 dask
</code></pre>

<h2>مخرجات التعلّم</h2>

<ul>
  <li>يستخدم أسماء ملفات ومجلدات ذات معنى ومختصرة، مع اعتماد إحدى الاستراتيجيات التالية: الطوابع الزمنية، تسلسل العمليات، أو بيانات وصفية ضمن اسم الملف. (CC1.3)</li>
  <li>يعرف كيفية التنقّل في نظام الملفات باستخدام كلٍ من الواجهة الرسومية (GUI) وسطر الأوامر (CLI). (CC1.4)</li>
  <li>يوثّق العلاقات بين الشيفرة والنتائج والبيانات الوصفية. (CC1.5)</li>
  <li>يستخدم مدير حزم لتثبيت وإدارة تبعيات البرمجيات. (CC1.10)</li>
  <li>يفهم التمثيلات الحاسوبية لأنواع البيانات العددية. (CC2.1)</li>
  <li>يفهم المصفوفات متعددة الأبعاد واستخدامها لتمثيل مجموعات البيانات المهيكلة مكانيًا وزمانيًا وعبر متغيرات متعددة. (CC2.3)</li>
  <li>يقيّم استخدام الموارد في سير عمل حاسوبي. (CC2.5)</li>
  <li>يفهم أنواع التوازي المختلفة وكيفية توسيع نطاق سير عمل حاسوبي مقيّد بالإنتاجية أو الذاكرة. (CC2.6)</li>
  <li>يستطيع تصحيح أخطاء سير العمل الحاسوبي عبر الاستدلال، أو عبارات الطباعة، أو نقاط التوقّف، أو مصحّح أخطاء تفاعلي. (CC2.7)</li>
  <li>على دراية بأنواع مجموعات البيانات المهيكلة المستخدمة في التطبيقات العلمية، بما في ذلك البيانات المكانية (نقطية ومتجهة) والبيانات الهرمية (مثل HDF5 و netCDF4). (CC2.8)</li>
  <li>يتم توثيق سير العمل الحاسوبي بتعليقات داخلية ووثائق خارجية. (CC4.3)</li>
  <li>يكتب دوال قصيرة وبسيطة بلا آثار جانبية. (CC4.9)</li>
</ul>

<h2>مجموعات البيانات المناخية المستخدمة</h2>

<ul>
  <li><a href="https://podaac.jpl.nasa.gov/dataset/TELLUS_GRAC-GRFO_MASCON_CRI_GRID_RL06.1_V3">شواذ تخزين المياه الأرضية من مهمتي NASA GRACE وGRACE-FO</a></li>
  <li>تقديرات الهطول المطري الشهرية لإفريقيا من <a href="https://www.chc.ucsb.edu/data/chirps">مجموعة بيانات CHIRPS (Climate Hazards Group InfraRed Precipitation with Station)</a></li>
  <li>بيانات التبخر-النتح المحتمل الشهرية من <a href="https://climatedataguide.ucar.edu/climate-data/terraclimate-global-high-resolution-gridded-temperature-precipitation-and-other-water">TerraClimate</a></li>
  <li>درجات حرارة الهواء اليومية (المتوسط، والحد الأدنى، والحد الأقصى) من <a href="https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/">إعادة التحليل MERRA-2 التابعة لمكتب النمذجة والاستيعاب العالمي في NASA</a></li>
</ul>

<h2>الشكر والتقدير</h2>

<p>
تم دعم هذا المنهاج بمنحة من برنامج التدريب
<strong>Transition to Open Science (TOPS)</strong>
التابع لوكالة ناسا (80NSSC23K0864)، وهو جزء من
<a href="https://nasa.github.io/Transform-to-Open-Science/">برنامج ناسا للتحوّل إلى العلم المفتوح (TOPS)</a>.
</p>

</div>

