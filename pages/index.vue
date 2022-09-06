<template>
  <div>
    <div class="h-screen bg-gray-600 shadow-xl p-4">
      <div class="font-semibold">Dashboard</div>
      <div class="min-h-screen w-full bg-slate-200 p-3">
        <!-- navbar for admin home -->
        <div class="h-10 w-full bg-slate-500 py-2 px-4 flex flex-row justify-end space-x-4">
          <p class="text-white">Hi Admin!</p>
          <div class="h-6 w-6 bg-slate-100 rounded-sm"></div>
        </div>
        <!-- end of nav -->
        <div class="h-auto flex flex-row justify-around space-x-4 py-5">
          <div class="h-full w-full flex flex-col items-center space-y-5">
            <div class="h-56 w-56 p-12 bg-white rounded-full">1</div>
            <div class="h-96 w-full bg-white rounded-lg">2</div>
          </div>
          <div class="w-full">
            <div class="h-full w-full flex flex-col items-center space-y-5">
            <div class="h-56 w-full p-12 bg-white rounded-lg">3</div>
            <div class="h-96 w-full bg-white rounded-lg">4</div>
          </div>
          </div>
          <div class="w-full"><div class="h-full w-full p-12 bg-white rounded-lg">
            <div>5</div>
          </div></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: "default",
  data() {
    return {
      isLoading: false,
    };
  },
};
</script>

<style></style>
