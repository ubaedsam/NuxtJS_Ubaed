<template>
  <div class="p-4 background">
    <div>
      <section id="about" class="pt-10 pb-10">
        <div class="container">
            <div class="row text-center mb-3">
                <div class="col">
                    <h4 class="font-semibold text-lg text-blue-600 mt-3">About Me</h4>
                    <p class="font-semibold text-grey-500 mb-2 mt-2">Ubaed Shibghahtallah Ashri Muharam</p>
                    <p class="font-semibold text-grey-500">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Veritatis eius architecto saepe quidem enim, laudantium, natus, molestiae atque nisi perspiciatis iusto? Explicabo sed, amet unde, non neque, itaque corrupti iste esse eaque
                        velit dolores error. Non illum labore impedit ab? Consequatur molestias nemo aliquid accusamus consectetur suscipit enim quas corporis qui amet sapiente veritatis ipsa voluptas quam nesciunt sunt, molestiae accusantium facilis
                        nulla aut! Alias ipsam vero dignissimos debitis autem.</p>
                </div>
            </div>
        </div>
    </section>
    </div>
    <div>
      <section id="fruit" class="pt-10 pb-10">
        <div class="container">
            <div class="row text-center mb-3">
                <h4 class="font-semibold text-lg text-blue-600">Fruit</h4>
                <div class="col mt-3">
                    <p class="font-semibold text-lg text-blue-600 mt-2 mb-2">Banana</p>
                    <img src="http://www.jquery-az.com/html/images/banana.jpg" title="Title of image" class="rounded img-fluid" alt="Banana" />
                </div>
                <div class="col mt-3">
                    <p class="font-semibold text-lg text-blue-600 mt-2 mb-2">Strawberries</p>
                    <img src="http://www.jquery-az.com/html/images/strawberries.jpg" title="Title of image" class="rounded img-fluid" alt="strawberries" />
                </div>
            </div>
        </div>
    </section>
    </div>
    <div>
      <section id="movie" class="pt-10 pb-10">
        <div class="container">
            <div class="row text-center mb-3">
                <h1 class="font-semibold text-lg text-blue-600">Movie</h1>
                <div class="col">
                    <p class="font-semibold text-lg text-blue-600 pt-3 mb-2">Tutorial Apa Itu HTML</p>
                    <iframe class="sm:text-center" width="310" height="200" src="https://www.youtube.com/embed/Q2VqCG13ejA?controls=0">
                    </iframe>
                </div>
                <div class="col pt-5">
                    <NuxtLayout :name="layouts.index">
                        <p class="font-semibold text-lg text-center">Playlist Tutorial HTML</p>
                        <ul>
                            <li class="font-semibold html">1. Pendahuluan HTML</li>
                            <li class="font-semibold html">2. Hello World</li>
                            <li class="font-semibold html">3. Code Editor</li>
                            <li class="font-semibold html">4. Tag HTML</li>
                            <li class="font-semibold html">5. Paragraf</li>
                        </ul>
                    </NuxtLayout>
                </div>
                <div class="col">
                    <p class="font-semibold text-lg text-blue-600 pt-3 mb-2">Tutorial Apa Itu CSS</p>
                    <iframe class="sm:text-center" width="310" height="200" src="https://www.youtube.com/embed/CleFk3BZB3g?controls=0">
                    </iframe>
                </div>
                <div class="col pt-5">
                    <NuxtLayout :name="layouts.index">
                        <p class="font-semibold text-lg text-center">Playlist Tutorial CSS</p>
                        <ul>
                            <li class="font-semibold css">1. Pendahuluan css</li>
                            <li class="font-semibold css">2. Anatomi CSS</li>
                            <li class="font-semibold css">3. Penempatan CSS</li>
                            <li class="font-semibold css">4. Font Styling</li>
                            <li class="font-semibold css">5. Text Styling</li>
                        </ul>
                    </NuxtLayout>
                </div>
            </div>
        </div>
    </section>
    </div>
    <div>
      <section id="contact" class="pt-10 pb-20">
        <div class="container">
            <div class="w-full px-4">
                <div class="max-w-xl mx-auto text-center">
                    <h4 class="font-semibold text-2xl mb-2 sm:text-4xl lg:text-5xl text-blue-600">Contact</h4>
                    <h2 class="font-semibold text-blue-600 text-1xl mb-4">Hubungi Saya</h2>
                </div>
            </div>
            <form>
                <div class="w-full lg:w-2/3 lg:mx-auto">
                    <div class="w-full px-4 mb-8">
                        <label for="name" class="text-base font-semibold text-blue-600">Nama</label>
                        <input type="text" id="name" class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-primary focus:ring-1 focus:border-primary" />
                    </div>
                    <div class="w-full px-4 mb-8">
                        <label for="email" class="text-base font-semibold text-blue-600">Email</label>
                        <input type="email" id="email" class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-primary focus:ring-1 focus:border-primary" />
                    </div>
                    <div class="w-full px-4 mb-8">
                        <label for="message" class="text-base font-semibold text-blue-600">Pesan</label>
                        <textarea id="message" class="w-full bg-slate-200 text-dark p-3 rounded-md focus:outline-none focus:ring-primary focus:ring-1 focus:border-primary h-32"></textarea>
                    </div>
                    <div class="w-full px-4">
                        <button type="submit" class="text-base font-semibold text-white bg-blue-600 py-3 px-8 rounded-full w-full hover:opacity-80 hover:shadow-lg transition duration-500">Kirim</button>
                    </div>
                </div>
            </form>
        </div>
    </section>
    </div>
  </div>
</template>

<style lang="postcss" scoped>
.background {
  @apply bg-gray-200;
}
.pisang {
  @apply text-blue-300;
}

.strawberries {
  @apply text-red-300;
}

.video {
  @apply text-red-300;
}

.html{
  color: #CF6B34;
}

.css{
    color: #D9657E;
}
</style>

<script>
export default {
    data() {
        return {
            layouts: {
                index: "index"
            }
        }
    }
}
</script>