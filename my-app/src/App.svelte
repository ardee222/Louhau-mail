<script>
  let today = new Date();
  let year = today.getFullYear();
  let month = today.getMonth()+1;
  let date = today.getDate()
  let day = today.getDay();
  const day_change = {
    1:'一',
    2:'二',
    3:'三',
    4:'四',
    5:'五',
    6:'六',
    7:'日'
    }
</script>

<main>
  <div class="md:visible invisible absolute top-4 right-8">{year}年{month}月{date}日(星期{day_change[day]})</div>
  <div class="md:visible invisible positive max-w-xs w-full max-h-screen h-screen bg-white absolute left-0 top-0 flex flex-col p-6">
    <div class="flex m-4">
      <div class="text-bold text-xl bg-green-200 text-orange-300 w-10 h-10 rounded-lg pt-1">
        <div>LH</div>
      </div>
      <div class="my-2 mx-6 text-xl">Louhau mail</div>
    </div>
    <div class="flex my-4 p-4 bg-gray-400 hover:bg-gray-500 rounded-lg w-40 drop-shadow-lg">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125" />
      </svg>
      <div class="px-4">撰寫</div>  
    </div>
    <div class="flex mt-2 p-4 hover:bg-green-100 rounded-lg">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25" />
      </svg>
      <a href="https://www.louhau.edu.mo/" class="mb-2 mx-6 text-black">返回學生天地</a>
    </div>
    <div class="flex mt-2 p-4 hover:bg-green-100 rounded-lg">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
      </svg>      
      <a href="https://www.louhau.edu.mo/" class="mb-2 mx-6 text-black">收件匣</a>
    </div>
    <div class="flex mt-2 p-4 hover:bg-green-100 rounded-lg">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0" />
      </svg>
      <a href="https://www.louhau.edu.mo/" class="mb-2 mx-6 text-black">新信息</a>
    </div>
    <div class="absolute top-12 right-[-16px] w-8 h-8 rounded-full bg-green-300 hover:bg-green-400 flex justify-center items-center">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
      </svg>
    </div>
  </div>

  <input class="max-w-sm w-screen p-2 rounded-lg bg-gray-500 focus:bg-white focus:border" type="text" placeholder="搜尋郵件">
  <div class="xl:w-xl sm:w-sm rounded-xl max-h-screen h-screen bg-white mx-auto my-10 p-4">
    <div class="flex place-content-between mb-2 mx-4">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
        <path stroke-linecap="round" stroke-linejoin="round" d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0l3.181 3.183a8.25 8.25 0 0013.803-3.7M4.031 9.865a8.25 8.25 0 0113.803-3.7l3.181 3.182m0-4.991v4.99" />
      </svg>
      <div class="flex space-x-2">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
        </svg>
        
      </div>
    </div>
    <hr>
    <div>暫時冇信息</div>
  </div>
</main>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@500&family=Secular+One&display=swap');
*{
  font-family: 'Noto Sans TC', sans-serif;
}

</style>
