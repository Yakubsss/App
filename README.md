import DataImage from "./data";
import { listTools, listProyek } from "./data";
import "./index.css";

function App() {
  
  return (
    
    <>
      <div
        id="beranda"
        className="hero min-h-screen flex items-center pt-6 xl:gap-0 gap-6 grid-cols-1 scroll-mt-32 mt-20 px-6 lg:px-20"
      >
        {/* Bagian Kiri: Teks */}
        <div className="animate__animated animate__fadeInUp animate__delay-2s w-full lg:w-1/2">
          {/* Quote Card */}
          <div className="flex items-center gap-3 mb-8 bg-zinc-800/50 w-fit p-3 pr-6 rounded-full border border-zinc-700 backdrop-blur-sm shadow-lg">
            <img
              src={DataImage.HeroImage}
              alt="Profile"
              className="w-10 h-10 rounded-full object-cover border-2 border-purple-500"
              loading="lazy"
            />
            <q className="text-sm text-zinc-300 italic font-medium">
              Keinginan yang diusahakan pasti akan terwujud 😊
            </q>
          </div>

          {/* Judul Utama */}
          <h1 className="text-5xl lg:text-6xl font-extrabold mb-6 leading-tight text-white">
            I'm{" "}
            <span className="text-transparent bg-clip-text bg-linear-to-r from-purple-500 to-pink-500">
              Yakub Vebrian
            </span>
          </h1>
          <p className="text-lg lg:text-xl mb-8 opacity-70 text-justify max-w-xl text-zinc-400 leading-relaxed border-l-4 border-purple-600 pl-4">
            Passionate in Electrical Power Systems, with focus on distribution
            transformer load analysis, phase balancing, and improving
            reliability of distribution networks through technical evaluation
            and practical field experience.
          </p>
          <div className="flex sm:gap-4 flex-wrap gap-3 mb-10">
            <a
              href="#"
              className="group bg-purple-600 px-7 py-3.5 rounded-xl hover:bg-purple-700 transition-all shadow-lg shadow-purple-900/50 flex items-center gap-2 font-semibold"
            >
              Download CV
              <i className="ri-download-2-fill ri-lg group-hover:-translate-y-1 transition-transform"></i>
            </a>
            <a
              href="#kontak"
              className="group bg-zinc-800 px-7 py-3.5 rounded-xl hover:bg-zinc-700 border border-zinc-700 hover:border-purple-500 transition-all flex items-center gap-2 font-semibold text-white"
            >
              Lets Talk
              <i className="ri-arrow-right-fill ri-lg group-hover:translate-x-1 transition-transform"></i>
            </a>
          </div>

          <div className="flex items-center gap-4 pt-4 border-t border-zinc-800"></div>
        </div>
       
        <div className="animate__animated animate__fadeInUp animate__delay-3s w-full lg:w-1/2 flex justify-center lg:justify-end relative">
          <div className="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-75 h-75 bg-purple-600/30 rounded-full blur-[100px] -z-10"></div>

       
          <div className="relative group">
            <div className="absolute -inset-2 bg-linear-to-r from-blue-600 via-purple-500 to-pink-500 rounded-3xl blur opacity-40 group-hover:opacity-70 transition duration-500"></div>

            {/* Container Gambar */}
            <div className="relative rounded-3xl overflow-hidden p-1 bg-zinc-900">
              <img
                src={DataImage.HeroImage}
                alt="Hero"
                className="w-full max-w-md lg:max-w-full rounded-3xl aspect-square object-cover grayscale group-hover:grayscale-0 transition duration-500 shadow-2xl"
                loading="lazy"
              />
            </div>
          </div>
        </div>
      </div>

      {/* --- TENTANG SECTION --- */}
<div id="tentang" className="tentang scroll-mt-32 mt-32 px-6 lg:px-20">
  <div className="xl:w-2/3 lg:w-3/4 w-full mx-auto">
    <div className="flex items-center gap-4 mb-8" data-aos="fade-up">
      <div className="h-px bg-zinc-700 flex-1"></div>
      <h1 className="text-lg font-semibold tracking-wide bg-violet-700 px-6 py-2 rounded-xl text-white shadow-lg shadow-violet-900/50">
        About Me
      </h1>
      <div className="h-px bg-zinc-700 flex-1"></div>
    </div>

    <div data-aos="fade-up" data-aos-delay="100">
        <div 
        className="text-base/loose text-justify 
        bg-linear-to-br from-zinc-700/40 to-zinc-800/30 
        p-8 rounded-2xl leading-relaxed 
        border border-zinc-600/40 shadow-md relative overflow-hidden"
        >
     
        <div className="absolute top-0 right-0 w-32 h-32 bg-violet-600/10 rounded-full blur-3xl -mr-10 -mt-10"></div>
        <p className="relative z-10 text-zinc-300">
            Fresh graduate Bachelor of Engineering with a background in
            Electrical Power Systems and hands-on experience in power
            distribution operations and technical services through fieldwork and
            internships. Experienced in distribution network maintenance,
            transformer load imbalance analysis, and customer-side
            troubleshooting. Skilled in technical analysis using GNU Octave and
            ETAP, with exposure to applied engineering projects. Demonstrates a
            structured, analytical, and solution-oriented mindset, with strong
            adaptability in dynamic technical environments.
        </p>

       
        </div>
        </div>
    </div>

  </div>


      {/* --- EDUCATION SECTION --- */}
<div id="education" className="education scroll-mt-32 mt-32 py-10 px-6 lg:px-20">
  <div className="xl:w-2/3 lg:w-3/4 w-full mx-auto">
    
    
    <h1 
      className="text-4xl/snug font-bold mb-10 text-center bg-linear-to-r from-violet-600 to-amber-400 w-fit mx-auto px-6 py-2 rounded-xl shadow-md text-white"
      data-aos="fade-up"
    >
      Education
    </h1>

  
    <div className="grid md:grid-cols-2 gap-8" data-aos="fade-up" data-aos-delay="100">
      
     
      <div 
        className="text-base/loose text-justify 
        bg-linear-to-br from-zinc-700/40 to-zinc-800/30 
        p-8 rounded-2xl leading-relaxed 
        border border-zinc-600/40 shadow-md hover:border-violet-500 transition-all duration-300"
      >
        <div className="flex flex-col items-center text-center">
          {/* Icon */}
          <div className="w-20 h-20 bg-violet-600/20 rounded-full flex items-center justify-center mb-4">
            <i className="ri-school-fill ri-2x text-violet-500"></i>
          </div>
          
          {/* University Name */}
          <h2 className="flex items-center justify-center py-2 font-bold text-white text-2xl">
            Bachelor Tidar University
          </h2>

          {/* Degree */}
          <h2 className="flex items-center justify-center font-semibold text-xl text-zinc-300 mb-2">
            S1 - 
            <span className="text-violet-400 font-bold ml-2">
              Electrical Engineering
            </span>
          </h2>
          
          {/* GPA Badge */}
          <div className="mt-4 px-6 py-3 bg-zinc-800/80 rounded-xl border border-zinc-600">
            <span className="text-amber-400 font-bold text-xl">
              GPA = 3.47
            </span>
          </div>
        </div>
      </div>

      {/* Right: Laboratory Assistant */}
      <div className="space-y-6">
        <h2 className="text-2xl font-bold text-white flex items-center gap-2">
          <i className="ri-flask-line text-amber-500"></i>
          Laboratory Assistant
        </h2>

        
        <div className="group bg-zinc-800/50 p-6 rounded-2xl border border-zinc-700 hover:bg-zinc-800 hover:border-amber-500 transition-all duration-300 cursor-pointer">
          <div className="flex items-start gap-4">
            <div className="w-12 h-12 bg-amber-500/20 rounded-xl flex items-center justify-center text-amber-500 group-hover:bg-amber-500 group-hover:text-zinc-900 transition-colors">
              <i className="ri-settings-3-fill ri-xl"></i>
            </div>
            <div>
              <h3 className="font-bold text-lg text-white group-hover:text-amber-400 transition-colors">
                Praktikum Sistem Kendali
              </h3>
              <p className="text-sm text-zinc-500 mt-1">
                Membantu mahasiswa dalam memahami konsep kontrol & simulasi PID
              </p>
            </div>
          </div>
        </div>

       
        <div className="group bg-zinc-800/50 p-6 rounded-2xl border border-zinc-700 hover:bg-zinc-800 hover:border-amber-500 transition-all duration-300 cursor-pointer">
          <div className="flex items-start gap-4">
            <div className="w-12 h-12 bg-amber-500/20 rounded-xl flex items-center justify-center text-amber-500 group-hover:bg-amber-500 group-hover:text-zinc-900 transition-colors">
              <i className="ri-flashlight-fill ri-xl"></i>
            </div>
            <div>
              <h3 className="font-bold text-lg text-white group-hover:text-amber-400 transition-colors">
                Praktikum Analisis Sistem Tenaga
              </h3>
              <p className="text-sm text-zinc-500 mt-1">
                Membantu analisis aliran daya, stabilitas & proteksi jaringan
              </p>
            </div>
          </div>
        </div>

      </div>

    </div>
  </div>
</div>

      {/* SKILL */}

      <div id="skill" className="tools scroll-mt-32 mt-32">
        <h1
          className="text-4xl/snug font-bold mb-6 text-center 
            bg-linear-to-r from-violet-700 to-purple-600 
            w-fit mx-auto px-6 py-2 rounded-xl shadow-md
            transition duration-300 hover:scale-105 hover:shadow-lg"
        >
          SKILL
        </h1>
        <div
          className="tools-box mt-14 grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 
          grid-cols-1 gap-4 "
        >
          {listTools.map((tool) => (
            <div
              className=" flex items-center gap-2 p-3 border border-zinc-600 rounded-md
              group transition duration-300 hover:-translate-y-1 hover:shadow-xl"
              key={tool.id}
            >
              <img
                src={tool.gambar}
                alt="Tools Image"
                className="w-14 bg-white p-1 
                 group-hover:bg-zinc-900 border border-zinc-700 rounded-full"
                loading="lazy"
              />
              <div>
                <h4 className="font-bold ">{tool.nama}</h4>
                <p className="opacity-50">{tool.ket}</p>
              </div>
            </div>
          ))}
        </div>
      </div>

      {/* proyek */}
      <div
        id="proyek"
        className="proyek scroll-mt-32 mt-32 py-10 px-6 lg:px-6 pt-1 xl:gap-0 gap-6 grid-cols-1"
      >
        <h1 className="text-center text-4xl font-bold mb-2">Proyek</h1>
        <p className="text-base text-center opacity-60">
          proyek yang saya buat
        </p>
        <div className="proyek-box mt-14 grid lg:grid-cols-2 md:grid-cols-2 grid-cols-1 gap-4 max-w-6xl mx-auto">
          {listProyek.map((proyek) => (
            <div key={proyek.id} className="p-4 bg-zinc-600/50 rounded-md ">
              <img src={proyek.gambar} alt="Proyek Image" loading="lazy" />

              <div>
                <h1 className="text-2xl font-bold my-4">{proyek.nama}</h1>
                <p className="text-base/loose mb-4">{proyek.desk}</p>
                <div className="flex flex-wrap gap-2">
                  {proyek.tools.map((tool, index) => (
                    <p
                      className="inline-block py-1 px-3  bg-amber-400 
                      text-black rounded-md font-semibold hover:bg-amber-300 transition"
                      key={index}
                    >
                      {tool}
                    </p>
                  ))}
                </div>
                <div>
                  <div className="mt-8 text-center">
                    <a
                      href="#"
                      className="bg-violet-700 p-3 rounded-lg border border-zinc-600
                  hover:bg-zinc-600"
                    >
                      view detail
                    </a>
                  </div>
                </div>
              </div>
            </div>
          ))}
        </div>
      </div>

      {/* Header */}
<div className="text-center mb-12" data-aos="fade-up">
  <div className="flex items-center justify-center gap-4 mb-4">
    <div className="h-px bg-zinc-700 w-16"></div>
    <h1 className="text-4xl font-bold text-white">Kontak</h1>
    <div className="h-px bg-zinc-700 w-16"></div>
  </div>
  <p className="text-base/loose text-zinc-400">
    Mari terhubung dengan saya
  </p>
</div>

<div className="grid lg:grid-cols-3 gap-8" data-aos="fade-up" data-aos-delay="100">
  
  {/* Kolom Kiri: Info Kontak */}
  <div className="lg:col-span-1 space-y-6">
    <div className="bg-zinc-800/50 p-6 rounded-2xl border border-zinc-700 hover:border-violet-500 transition-colors">
      <div className="w-12 h-12 bg-violet-600/20 rounded-xl flex items-center justify-center text-violet-500 mb-4">
        <i className="ri-mail-fill ri-xl"></i>
      </div>
      <h3 className="text-white font-bold mb-1">Email</h3>
      <p className="text-zinc-400 text-sm">yakubvebrian@gmail.com</p>
    </div>

    <div className="bg-zinc-800/50 p-6 rounded-2xl border border-zinc-700 hover:border-violet-500 transition-colors">
      <div className="w-12 h-12 bg-violet-600/20 rounded-xl flex items-center justify-center text-violet-500 mb-4">
        <i className="ri-map-pin-user-fill ri-xl"></i>
      </div>
      <h3 className="text-white font-bold mb-1">Lokasi</h3>
      <p className="text-zinc-400 text-sm">Magelang, Jawa Tengah, Indonesia</p>
    </div>

    <div className="bg-zinc-800/50 p-6 rounded-2xl border border-zinc-700 hover:border-violet-500 transition-colors">
      <div className="w-12 h-12 bg-violet-600/20 rounded-xl flex items-center justify-center text-violet-500 mb-4">
        <i className="ri-links-fill ri-xl"></i>
      </div>
      <h3 className="text-white font-bold mb-3">Sosial Media</h3>
      <div className="flex gap-3">
        <a href="#" className="w-10 h-10 bg-zinc-700 rounded-lg flex items-center justify-center text-white hover:bg-violet-600 transition">
          <i className="ri-instagram-line"></i>
        </a>
        <a href="#" className="w-10 h-10 bg-zinc-700 rounded-lg flex items-center justify-center text-white hover:bg-violet-600 transition">
          <i className="ri-linkedin-box-line"></i>
        </a>
        <a href="#" className="w-10 h-10 bg-zinc-700 rounded-lg flex items-center justify-center text-white hover:bg-violet-600 transition">
          <i className="ri-github-line"></i>
        </a>
      </div>
    </div>
  </div>


  <div className="lg:col-span-2">
    <form
      action="https://formsubmit.co/yakubvebrian@gmail.com"
      method="POST"
      className="bg-zinc-800 p-8 rounded-2xl border border-zinc-700 shadow-xl"
      autoComplete="off"
    >
      {/* Hidden Inputs for FormSubmit */}
      <input type="hidden" name="_subject" value="Pesan baru dari Portfolio" />
      <input type="hidden" name="_captcha" value="false" />

  
        {/* Nama */}
        <div className="space-y-2">
          <label className="text-sm font-semibold text-zinc-300">Nama Lengkap</label>
          <div className="relative">
            <i className="ri-user-line absolute left-3 top-3 text-zinc-500"></i>
            <input
              type="text"
              name="nama"
              placeholder="Nama kamu..."
              className="w-full bg-zinc-900 border border-zinc-600 text-white pl-10 p-3 rounded-lg focus:outline-none focus:border-violet-500 focus:ring-1 focus:ring-violet-500 transition"
              required
            />
          </div>
        </div>

        {/* Email */}
        <div className="space-y-2">
          <label className="text-sm font-semibold text-zinc-300">Email</label>
          <div className="relative">
            <i className="ri-mail-line absolute left-3 top-3 text-zinc-500"></i>
            <input
              type="email"
              name="email"
              placeholder="email@kamu.com"
              className="w-full bg-zinc-900 border border-zinc-600 text-white pl-10 p-3 rounded-lg focus:outline-none focus:border-violet-500 focus:ring-1 focus:ring-violet-500 transition"
              required
            />
          </div>
        </div>
      </div>

      {/* Pesan */}
      <div className="space-y-2 mb-6">
        <label className="text-sm font-semibold text-zinc-300">Pesan</label>
        <div className="relative">
          <i className="ri-message-3-line absolute left-3 top-3 text-zinc-500"></i>
          <textarea
            name="pesan"
            placeholder="Halo Yakub, saya tertarik dengan..."
            rows="5"
            className="w-full bg-zinc-900 border border-zinc-600 text-white pl-10 p-3 rounded-lg focus:outline-none focus:border-violet-500 focus:ring-1 focus:ring-violet-500 transition resize-none"
            required
          ></textarea>
        </div>
      </div>


      <button
        type="submit"
        className="w-full bg-linear
        -to-r from-violet-600 to-purple-600 p-4 rounded-lg cursor-pointer font-bold text-white hover:from-violet-500 hover:to-purple-500 transition-all transform hover:scale-[1.02] shadow-lg shadow-violet-900/50 flex items-center justify-center gap-2"
      >
        <i className="ri-send-plane-fill"></i>
        Kirim Pesan
      </button>
    </form>
  </div>

</div>
    </>
  );
}
export default App; //*}
