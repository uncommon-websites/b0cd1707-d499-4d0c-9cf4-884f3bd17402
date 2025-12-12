<script>
</script>

<section class="bg-gray-900 text-white py-24 overflow-hidden relative">
  <!-- Background gradient effect -->
  <div class="absolute inset-0 bg-gradient-to-b from-gray-800 to-black opacity-100"></div>
  
  <div class="relative max-w-[1200px] mx-auto px-6 text-center">
    <h2 class="text-5xl font-bold mb-6 tracking-tight leading-tight">
      AI-Powered Project<br>Documentation
    </h2>
    <p class="text-gray-300 text-lg max-w-2xl mx-auto mb-16 leading-relaxed">
      Industry-specific AI agents that understand construction workflows. Cogram automatically organizes emails, generates reports, and keeps your entire project team synchronized—no manual filing required.
    </p>

    <!-- UI Mockup -->
    <div class="bg-white rounded-xl shadow-2xl overflow-hidden text-left text-gray-900 mx-auto max-w-[1000px] border border-blue-400/30">
      <!-- Window Controls -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-400"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
          <div class="w-3 h-3 rounded-full bg-green-400"></div>
        </div>
        <div class="ml-4 flex items-center gap-2 text-xs font-medium text-gray-600 bg-white px-2 py-1 rounded border border-gray-200 shadow-sm">
           <span class="w-3 h-3 bg-gray-800 rounded-full flex items-center justify-center text-[8px] text-white">A</span>
           Atlas
           <span class="text-gray-400">▼</span>
        </div>
      </div>

      <div class="flex h-[500px]">
        <!-- Sidebar -->
        <div class="w-48 bg-gray-50 border-r border-gray-200 p-3 flex flex-col gap-1">
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🕒</span> Recent
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-900 bg-white shadow-sm border border-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📋</span> Active Projects
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📝</span> RFIs
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📄</span> Submittals
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📧</span> Email Archive
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📂</span> All Documents
          </div>
          
          <div class="mt-auto text-[10px] text-gray-400 px-2">247 documents</div>
        </div>

        <!-- Main List -->
        <div class="flex-1 bg-white flex flex-col">
          <div class="border-b border-gray-100 p-3">
             <div class="relative">
                <span class="absolute left-2 top-1.5 text-gray-400 text-xs">🔍</span>
                <input type="text" placeholder="Search projects and documents..." class="w-full bg-gray-50 border border-gray-200 rounded pl-7 pr-3 py-1 text-xs focus:outline-none focus:border-teal-500">
             </div>
          </div>
          <div class="flex-1 overflow-y-auto">
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-teal-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">HC</div>
                   <span class="text-xs font-medium text-gray-700">Harbor Center Tower</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-teal-600">Active · PRJ-2847</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 bg-teal-50/50 cursor-pointer">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-teal-100 text-teal-600 rounded flex items-center justify-center text-[8px]">WP</div>
                   <span class="text-xs font-medium text-gray-900">Westside Plaza Renovation</span>
                </div>
                <div class="text-[10px] text-gray-400">PRJ-2901</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-teal-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">MB</div>
                   <span class="text-xs font-medium text-gray-700">Madison Bridge Project</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-teal-600">Active · PRJ-2823</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-teal-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">RC</div>
                   <span class="text-xs font-medium text-gray-700">Riverside Commons</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-teal-600">Planning · PRJ-2798</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-teal-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">TC</div>
                   <span class="text-xs font-medium text-gray-700">Tech Campus Phase 2</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-teal-600">PRJ-2756</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-teal-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">OP</div>
                   <span class="text-xs font-medium text-gray-700">Oak Park Residential</span>
                </div>
             </div>
          </div>
        </div>

        <!-- Right Panel -->
        <div class="w-80 bg-white border-l border-gray-200 flex flex-col">
          <div class="p-3 border-b border-gray-100 flex justify-between items-center">
             <span class="text-[10px] font-bold text-gray-400 uppercase tracking-wider">Project Activity</span>
             <button class="text-[10px] border border-gray-200 rounded px-2 py-1 hover:bg-gray-50 flex items-center gap-1">
                <span>🔔</span> Subscribe
             </button>
          </div>
          
          <div class="p-4 flex-1 overflow-y-auto">
             <div class="text-[10px] font-bold text-gray-400 uppercase tracking-wider mb-2">Recent Updates</div>
             
             <!-- Activity Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-orange-400"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">Draft report</span>
                   <span class="text-[10px] text-gray-400">2 hours ago</span>
                </div>
             </div>

             <!-- Activity Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-teal-500">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-teal-500"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">RFI #2847 Resolved</span>
                   <span class="text-[10px] text-gray-400">Sarah Chen</span>
                </div>
                <div class="text-[10px] text-gray-600 mb-2">
                   Structural engineer approved the beam specification change for Level 3 west wing
                </div>
                <span class="inline-block px-1.5 py-0.5 bg-teal-100 text-teal-700 text-[9px] rounded font-medium">Resolved</span>
             </div>

             <div class="flex items-center gap-2 mb-4 pl-4">
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <div class="w-1 h-1 bg-gray-300 rounded-full"></div>
                <span class="text-[10px] text-gray-400">Show 18 more updates</span>
             </div>

             <!-- Activity Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-gray-300"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-500">Meeting Minutes</span>
                   <span class="text-[10px] text-gray-400">Mike Torres</span>
                </div>
                <div class="text-[10px] text-gray-500">
                   Weekly coordination meeting - discussed HVAC routing conflicts and schedule adjustments
                </div>
             </div>
             
             <!-- Activity Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-gray-300"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-500">Submittal Approved</span>
                   <span class="text-[10px] text-gray-400">Alex Rivera</span>
                </div>
                <div class="text-[10px] text-gray-500">
                   Curtain wall system submittal package approved with minor comments for fabrication
                </div>
             </div>
          </div>
          
          <div class="p-3 border-t border-gray-100 bg-gray-50 flex justify-between items-center">
             <div class="flex items-center gap-2 text-[10px] text-gray-500">
                <button class="hover:text-gray-900">✕</button>
                <span>Filter by type</span>
             </div>
             <div class="flex gap-2">
                <button class="bg-white border border-gray-200 text-gray-700 text-[10px] px-2 py-1 rounded hover:bg-gray-50">View All</button>
                <button class="bg-black text-white text-[10px] px-2 py-1 rounded hover:bg-gray-800">Open Project</button>
             </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Bottom Integration Info -->
    <div class="mt-12 flex items-center justify-center gap-4 bg-gray-800 rounded-lg p-4 max-w-4xl mx-auto border border-gray-700">
       <div class="flex items-center gap-4 border-r border-gray-600 pr-4">
          <div class="w-8 h-8 bg-white rounded flex items-center justify-center font-bold text-black text-xs">📧</div>
          <div class="w-8 h-8 bg-blue-600 rounded flex items-center justify-center font-bold text-white text-xs">📅</div>
          <div class="w-8 h-8 bg-green-600 rounded flex items-center justify-center font-bold text-white text-xs">💬</div>
       </div>
       <p class="text-xs text-gray-300 text-left flex-1">
          Cogram integrates seamlessly with your existing tools. Connect email, calendar, Slack, and project management platforms to automate documentation across your entire workflow.
       </p>
       <button class="bg-white text-black px-3 py-1.5 rounded text-xs font-semibold hover:bg-gray-100">Get started</button>
    </div>
  </div>
</section>
