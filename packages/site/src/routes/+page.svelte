<script>
  // No script logic needed for static content
  const cv_email = import.meta.env.VITE_CV_EMAIL
  const cv_phone = import.meta.env.VITE_CV_PHONE
</script>

<div class="min-h-screen text-gray-800">
  <div class="page pt-8">
    <!-- Body -->
    <div class="grid grid-cols-[var(--left-side-width)_auto_1fr]">
      <!-- Left column -->

      <aside class="space-y-8">
        <figure class="!m-0 flex items-center justify-center pb-8 pt-8">
          <img
            src="./portrait1.jpg"
            alt="my face"
            class=" h-[192px] w-[192px] rounded-full object-cover [object-position:40%_15%]"
          />
        </figure>

        <!-- Contact -->
        <section class="px-8">
          <h2 class="mb-2 text-xl font-extrabold uppercase text-gray-900">Contact</h2>
          <address class="grid grid-cols-[auto_1fr] items-center gap-x-1.5 gap-y-1 text-gray-700">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="h-4 w-4"
              ><path
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M13.832 16.568a1 1 0 0 0 1.213-.303l.355-.465A2 2 0 0 1 17 15h3a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2A18 18 0 0 1 2 4a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v3a2 2 0 0 1-.8 1.6l-.468.351a1 1 0 0 0-.292 1.233a14 14 0 0 0 6.392 6.384"
              /></svg
            ><a href={`tel:${cv_phone}`}>{cv_phone} </a>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="lucide lucide-mail-icon lucide-mail h-4 w-4"
              ><path d="m22 7-8.991 5.727a2 2 0 0 1-2.009 0L2 7" /><rect
                x="2"
                y="4"
                width="20"
                height="16"
                rx="2"
              /></svg
            ><a href={`mailto:${cv_email}`}>{cv_email}</a>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              class="h-4 w-4"
              ><g
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                ><path
                  d="M20 10c0 4.993-5.539 10.193-7.399 11.799a1 1 0 0 1-1.202 0C9.539 20.193 4 14.993 4 10a8 8 0 0 1 16 0"
                /><circle cx="12" cy="10" r="3" /></g
              ></svg
            > <span class="not-italic">Helsinki, Finland</span>
          </address>
        </section>

        <!-- Skills -->
        <section class="px-8">
          <h2 class=" mb-2 text-xl font-extrabold uppercase text-gray-900">Skills</h2>
          <ul class="space-y-2 text-sm">
            <li>
              <strong>Finnish:</strong> Native <br /> <strong>English:</strong> Fluent
            </li>
            <li>
              <strong>Languages & Frameworks:</strong> Python, JavaScript, TypeScript, SQL, Node.js,
              React, Svelte
            </li>
            <li>
              <strong>AI / ML Tools:</strong> TensorFlow, Keras, scikit-learn, LangChain
            </li>
            <li>
              <strong>Cloud & DevOps:</strong> Docker, AWS, Azure, IBM Cloud
            </li>
            <li>
              <strong>Data & Databases:</strong> Pandas, PostgreSQL
            </li>
            <li>
              <strong>LLM / NLP:</strong> Prompt design, evaluation pipelines, conversational AI
            </li>
            <li>
              <strong>Other:</strong> Agile, Git
            </li>
          </ul>
        </section>
      </aside>

      <!-- Divider -->
      <div
        aria-hidden="true"
        class="h-[90%] w-[3px] self-center justify-self-center rounded-full bg-transparent"
      ></div>

      <!-- Right column -->
      <main class="space-y-6 px-0 pr-8 pt-8">
        <!-- Profile -->
        <section>
          <!-- Header -->
          <div class=" pb-6">
            <h1 class="ml-[-2px] text-5xl font-bold text-gray-900">Lauri Koivisto</h1>
            <p class="mt-1 pl-[1px] text-lg text-gray-700">Data & AI Engineer</p>
            <p class="mt-1 pl-[1px] text-sm text-gray-700">
              Python • LLMs • Full-Stack Development
            </p>
          </div>
          <p class=" pl-[1.5px] italic text-gray-700">
            » Data & AI Engineer with expertise in natural language processing and AI-powered
            solution design. Skilled in Python, data engineering, and full-stack development with
            modern frameworks such as React, Node.js, and Docker. Experienced in applying machine
            learning and LLM technologies to create scalable, production-ready systems. Strong
            background in agile collaboration, iterative development, and delivering measurable
            business impact through hands-on implementation.
          </p>
        </section>
        <!-- Work Experience -->
        <section>
          <h2 class=" text-[22px] font-extrabold uppercase text-gray-900">
            Selected Work Experience
          </h2>
          <hr class="border-t-3 mb-3 border-gray-600" />

          <div class="space-y-6 pl-[1px]">
            <!-- IBM Finland -->
            <div>
              <h3 class="text-lg font-bold">AI and Data Engineer — IBM Finland</h3>

              <p class="flex items-center gap-1.5 text-sm text-gray-600">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  class="h-3.5 w-3.5"
                  ><g
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    ><path d="M8 2v4m8-4v4" /><rect
                      width="18"
                      height="18"
                      x="3"
                      y="4"
                      rx="2"
                    /><path d="M3 10h18" /></g
                  ></svg
                > May 2022 – July 2025
              </p>
              <div class="mt-2 space-y-2 pl-[1.5px] text-gray-700">
                <p class=" text-gray-700">
                  For little over 3 years, I worked on several projects including AI translation,
                  evaluation, chatbot development, and image classification research. Designed and
                  implemented datasets and prompt templates to assess multilingual LLM translation
                  accuracy, leading to an 11% improvement over baseline models.
                </p>
                <p class=" text-gray-700">
                  Built and deployed a full-stack translation interface integrating React, Node.js,
                  and Docker for real-time translation workflows.
                </p>
                <p class=" text-gray-700">
                  Conducted CNN-based image classification research with TensorFlow and Keras,
                  optimizing model performance. Additionally, built public-sector chatbots using
                  Watson Assistant and Discovery, and provided training for chatbot maintainers.
                </p>
              </div>
            </div>

            <!-- Thesis Worker -->
            <div>
              <h3 class="text-lg font-bold">Thesis Worker — Aalto University</h3>
              <p class="flex items-center gap-1.5 text-sm text-gray-600">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  class="h-3.5 w-3.5"
                  ><g
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    ><path d="M8 2v4m8-4v4" /><rect
                      width="18"
                      height="18"
                      x="3"
                      y="4"
                      rx="2"
                    /><path d="M3 10h18" /></g
                  ></svg
                > April 2020 – Sep 2020
              </p>
              <p class="mt-2 pl-[1.5px] text-gray-700">
                For my thesis project I researched if adding new features to a Convolutional Neural
                Network (CNN) model would improve its accuracy in speaker recognition. I compared
                the model to a baseline and after evaluating the error rates my research found that
                features such as jitter and shimmer can improve speaker recognition.
              </p>
            </div>

            <!-- Web Developer -->
            <div>
              <h3 class="text-lg font-bold">Web Developer — Vaisala</h3>
              <p class="flex items-center gap-1.5 text-sm text-gray-600">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  class="h-3.5 w-3.5"
                  ><g
                    fill="none"
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    ><path d="M8 2v4m8-4v4" /><rect
                      width="18"
                      height="18"
                      x="3"
                      y="4"
                      rx="2"
                    /><path d="M3 10h18" /></g
                  ></svg
                >June 2018 – Sep 2018
              </p>
              <p class="mt-2 pl-[1.5px] text-gray-700">
                Developed backend and frontend solutions for the Weather Radar team using
                TypeScript, React, and Node.js. Integrated image export functionality from IRIS
                Focus to enable radar image display on go.vaisala.com/keravaradar.
              </p>
            </div>
          </div>
        </section>
      </main>
    </div>
  </div>
  <div class="page pt-8">
    <!-- Body -->
    <div class="">
      <!-- Education -->
      <section class="p-8">
        <h2 class="text-[22px] font-extrabold uppercase text-gray-900">Education</h2>
        <hr class="border-t-3 -ml-0.5 mb-3 border-gray-600" />
        <div class="space-y-4 pl-[1.5px]">
          <div>
            <h3 class="font-bold">
              M.Sc. (Technology), Speech and Signal Processing — Aalto University
            </h3>
            <p class="flex items-center gap-1.5 text-sm text-gray-600">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
                class="h-3.5 w-3.5"
                ><g
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  ><path d="M8 2v4m8-4v4" /><rect width="18" height="18" x="3" y="4" rx="2" /><path
                    d="M3 10h18"
                  /></g
                ></svg
              >2017 – 2025
            </p>
            <p class="mt-1 text-gray-700">
              Studied speech recognition, natural language processing, and machine learning methods
              for audio and linguistic data.
            </p>
          </div>
          <div>
            <h3 class="font-bold">
              B.Sc. (Technology), Automation and Systems Technology — Aalto University
            </h3>
            <p class="flex items-center gap-1.5 text-sm text-gray-600">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="24"
                height="24"
                viewBox="0 0 24 24"
                class="h-3.5 w-3.5"
                ><g
                  fill="none"
                  stroke="currentColor"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  ><path d="M8 2v4m8-4v4" /><rect width="18" height="18" x="3" y="4" rx="2" /><path
                    d="M3 10h18"
                  /></g
                ></svg
              >2014 – 2017
            </p>
            <p class="mt-1 text-gray-700">
              Studied control systems, robotics, and embedded automation.
            </p>
          </div>
        </div>
      </section>

      <!-- Projects -->
      <section class="p-8">
        <h2 class="text-[22px] font-extrabold uppercase text-gray-900">Projects</h2>
        <hr class="border-t-3 -ml-0.5 mb-3 border-gray-600" />

        <div class="space-y-4 pl-[1.5px]">
          <div>
            <a
              href="https://github.com/koodilauri/laurikoivisto-cv"
              class="font-medium text-blue-600 hover:underline">CV page</a
            >
            — Wrote a printable CV page with Svelte and Tailwind.
            <a
              href="https://github.com/koodilauri/laurikoivisto-cv"
              class="font-semibold hover:underline"
              >https://github.com/koodilauri/laurikoivisto-cv</a
            >
          </div>
          <div>
            <a
              href="https://koodilauri.github.io/"
              class="font-medium text-blue-600 hover:underline">Personal Portfolio</a
            >
            — Developed a Next.js + Tailwind CSS portfolio site to present projects and experience in
            a visually appealing format.
            <a
              href="https://github.com/koodilauri/koodilauri.github.io"
              class="font-semibold hover:underline"
              >https://github.com/koodilauri/koodilauri.github.io</a
            >
          </div>
          <div>
            <a
              href="https://github.com/koodilauri/speaker-verification"
              class="font-medium text-blue-600 hover:underline">Speaker Verification (Thesis)</a
            >
            — Trained a CNN model for speaker recognition with voice features like jitter & shimmer.
            <a
              href="https://github.com/koodilauri/speaker-verification"
              class="font-semibold hover:underline"
              >https://github.com/koodilauri/speaker-verification</a
            >
          </div>
          <div>
            <a
              href="http://go.vaisala.com/keravaradar/"
              class="font-medium text-blue-600 hover:underline">Vaisala Radar Web App</a
            >
            — Developed backend and frontend with TypeScript, React, and Node.js.
            <a
              href="https://github.com/koodilauri/weather-radar-snapshot-server"
              class="font-semibold hover:underline"
              >https://github.com/koodilauri/weather-radar-snapshot-server</a
            >
          </div>
          <div>
            <a
              href="https://d386g19k2b21z4.cloudfront.net/"
              class="font-medium text-blue-600 hover:underline">Speedrun Fansite</a
            >
            — Created a React/Node project for submitting and managing video game speedruns.
            <a
              href="https://github.com/koodilauri/monster-hunter-app-backend"
              class="font-semibold hover:underline"
              >https://github.com/koodilauri/monster-hunter-app-backend</a
            >
          </div>
        </div>
      </section>
    </div>
  </div>
</div>

<style lang="postcss">
  @reference "#app.css";
  :root {
    --left-side-width: 256px;
  }
  .page {
    @apply mx-[auto] flex min-h-[29.7cm] max-w-[800px] flex-col items-center px-4 text-sm md:px-8;
  }
  @page {
    size: A4;
  }
  @media print {
    .page {
      height: 29.7cm;
      width: 21cm;
    }
  }
</style>
