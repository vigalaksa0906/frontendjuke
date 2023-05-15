<template>
  <div>
    <!-- Some default layout shared across all pages -->
    <div>
      <section class="bg-gray-700 py-5">
        <h2 class="text-center text-yellow-400 text-5xl font-bold">
          Tutorial Membuat Telur Ceplok
        </h2>
      </section>
      <div class="grid grid-flow-col text-center p-2">
        <table class="border-Collapse border border-green-900">
          <thead>
            <tr>
              <th class="border border-green-600">Alat & Bahan</th>
              <th class="border border-green-600">Takaran</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="border border-green-600">Telur ayam</td>
              <td class="border border-green-600">2 butir</td>
            </tr>
            <tr>
              <td class="border border-green-600">Garam atau Masako</td>
              <td class="border border-green-600">1/4 sendok teh</td>
            </tr>
            <tr>
              <td class="border border-green-600">Minyak goreng</td>
              <td class="border border-green-600">1 sendok makan</td>
            </tr>
          </tbody>
        </table>
      </div>
      <br />
      <h2 class="mx-24">Berikut adalah tahapan membuat telur ceplok:</h2>
      <div class="mx-24 bg-gray-200 text-justify px-6">
        <br />
        <ol class="list-decimal">
          <li>Tuangkan minyak dalam wajan</li>
          <li>Panaskan wajan</li>
          <li>Pecahkan telur lalu taruh ke dalam wajan perlahan</li>
          <li>Taburkan sedikit garam atau masako</li>
          <li>Tunggu sebentar lalu balik telur</li>
          <li>Setelah matang angkat telur dan sajikan dalam piring</li>
        </ol>
        <br />
      </div>

      <h3 class="text-center text-yellow-400 text-3xl font-bold">
        Untuk lebih jelasnya bisa menonton video berikut ini:
      </h3>
      <div class="flex items-center justify-center">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/eTF457SjyVc"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
        ></iframe>
      </div>
      <footer>
        <p class="text-center">
          Copyright &copy; 2023. Viga Laksa Hardjanto<br />
        </p>
      </footer>
    </div>
    <slot />
  </div>
</template>